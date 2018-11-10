# sample-python

## pipenv
- install pyenv
  - brew install pyenv
  - pyenv install (version)
    - On Error: xcode-select --install (on Mac Mojave)
  ````
  CFLAGS="-I$(brew --prefix readline)/include -I$(brew --prefix openssl)/include -I$(xcrun --show-sdk-path)/usr/include" LDFLAGS="-L$(brew --prefix readline)/lib -L$(brew --prefix openssl)/lib" PYTHON_CONFIGURE_OPTS=--enable-unicode=ucs2 pyenv install -v 3.6.7
  ````
  - pyenv global (version)

  
- install pipenv
  - pipenv --python (version)
    - create Pipfile & lock
    
    
  - install packages
    - pipenv install (package)
     
    - pipenv shell (activate)
    
    - pipenv run (script_name)
      - run script
    
    - pipenv check
      - run security check etc
      
    