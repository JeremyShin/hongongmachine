# hongong-machine

# pyenv 설치
```shell
brew install pyenv pyenv-virtualenv
```

# 환경변수 설치
```shell
# ~/.zshrc
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv init -)"
```

# pyenv 사용하기
```shell
# 설치 가능한 Python 버전
$ pyenv install --list

# 특정한 버전 Python 설치
$ pyenv install 3.11.3

# 특정한 버전 Python 삭제
$ pyenv uninstall 3.11.3

# 설치된 Python list
$ pyenv versions

# 해당 Python 버전을 기본으로 설정
$ pyenv global 3.11.3
```
# pyenv-virtualenv 사용하기

```shell
#가상환경 만들기
# pyenv virtualenv [version] [name]
$ pyenv virtualenv 3.11.3 hongong
```

# python 시작하기
```shell
# 가상환경 시작하기
$ pyenv activate hongong

# 가상환경 종료하기
$ pyenv deactivate

# 가상환경 목룍보기
$ pyenv virtualenvs
```

reff : [Python(pyenv) 성치 및 버전관리](https://leesh90.github.io/environment/2021/04/03/python-install/)
