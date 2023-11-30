### 1. Choose a Directory in Your Home Folder
Select or create a directory in your home folder where you want to install Homebrew. For example, ~/homebrew.

### 2. Clone the Homebrew Repository
Use git to clone the Homebrew repository into this directory. If you don't have git installed, you may need to install it first (often available as a pre-installed package on many systems). The command will look something like this:
  ```
git clone https://github.com/Homebrew/brew ~/homebrew
  ```
Replace ~/homebrew with your chosen directory.

### 3. Add Homebrew to Your PATH
After cloning, you need to add the Homebrew bin directory to your PATH. Add the following line to your ~/.zshrc or ~/.bashrc file:
  ```
export PATH="$HOME/homebrew/bin:$PATH"
  ```
Again, replace $HOME/homebrew with the path to your Homebrew installation.

### 4. Apply the Changes
To apply the changes to your PATH, either restart your terminal or source your configuration file:
  ```
source ~/.zshrc  # If using Z shell
# or
source ~/.bashrc  # If using Bash
  ```
### 5. Verify the Installation
Once done, you can verify that Homebrew is installed correctly by running:
  ```
brew --version
  ```
### 6. Install gcc and g++
  ```
brew install gcc
  ```
if you still have the same proble you can complie with
```
clang for c
clang++ for cpp
```
