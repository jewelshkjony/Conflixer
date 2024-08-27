# 💥 Conflixer : A Powerful Tool To Resolve Conflicts Between Extensions
A CLI-tool for extension developers and extension users to quickly resolve conflicts between extensions.

![image](https://github.com/user-attachments/assets/e03f4cd8-efdf-438d-b5d8-d0bde1ac84bf)

## 💾 Installation
> **Note**: Before installing Enhancer, make sure that you've JDK 8 or above installed.


### 🪟 Windows
1. In the PowerShell, run:

    ```ps1
    iwr https://raw.githubusercontent.com/jewelshkjony/Conflixer/1.0.0/install.ps1 -useb | iex
    ```

2. To run Conflixer write `Conflixer` on terminal.

### 💻 Linux and macOS
1. In the terminal, run:

    ```sh
    curl https://raw.githubusercontent.com/jewelshkjony/Conflixer/1.0.0/install.sh -fsSL | sh
    ```

2. To run Conflixer write `chmod +x Conflixer.sh` on terminal.

## 🏃‍➡️ Quick start
Now, that you've installed Conflixer, let's try this tool.

1. Open the terminal and write `Conflixer`.
It'll ask you for two prompts.

    - `Enter aix to keep`: Set the path of the aix or drag the aix file here. The tool will parse this aix as reference.
    - `Enter aix to target`: Set the path of the aix or drag the aix file here. The tool will target the aix to generate new resolved aix.

3. Now the tool will build a new resolved aix within a very few seconds.
4. That's it. Now you can use the new resolved aix and the referenced aix together.
