# WindowsTools

Installez Chocolatey en suivant les instructions fournies dans le lien ci-dessous.

https://chocolatey.org/docs/installation

```
choco install virtualbox --version=7.1.4 -y
```
```
choco install vagrant --version=2.4.3 -y
```
```
choco install git -y
```
```
choco install corretto17jdk -y
```
```
choco install maven -y
```
```

choco install intellijidea-community -y
```
```
choco install vscode -y
```
```

# MacOS Tools

Installez Chocolatey en suivant les instructions fournies dans le lien ci-dessous.


https://brew.sh/

After installing homebrew
Create a file in users home directory with name .curlrc with content “-k” 
(-k without quotes and give a new line character after -k.)

Steps:

1. OpenTerminal
2. Execute below command
```
echo -k > ~/.curlrc
```
3. Execute below command to see -k in file ~/.curlrc 
```
cat ~/.curlrc
```

Run all the below commands in Terminal


### (virtualbox command is not For MacOs M1/M2)
```
brew install --cask virtualbox 
```
```
brew install --cask vagrant
```
```
brew install --cask vagrant-manager
```
```
brew install git
```
```
brew install openjdk@17
```
```
sudo ln -sfn $HOMEBREW_PREFIX/opt/openjdk@17/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk.jdk
```
```
exec zsh -l
```
```
brew install maven
```
```
brew install --cask visual-studio-code
```
```
brew install --cask intellij-idea
```
```
brew install --cask intellij-idea-ce
```
```

