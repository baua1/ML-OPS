# ML-OPS

Installing the pyenv python environment :

1. sudo apt install -y make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev

2. curl https://pyenv.run | bash

3. echo -e 'export PYENV_ROOT="$HOME/.pyenv"\nexport PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc

4. echo -e 'eval "$(pyenv init --path)"\neval "$(pyenv init -)"' >> ~/.bashrc

5. exec "$SHELL"

generating ssh key for connecting to github

1. ssh-keygen  -t rsa -b 4096 -C "registered email id"

2. ssh-add ~/.ssh/id_rsa

3. cat ~/.ssh/id_rsa.pub --> copy the key and paste it in the github key section.

4. git remote set-url origin git@github.com:username/your-repository.git
End to end machine learning training and deployment.
