# :bomb: Impulse
## Modern Denial-of-service ToolKit


<p align="center">
  <img src="https://raw.githubusercontent.com/7zx/overload/main/img/logo.png">
</p>

# :computer: Main window
<p align="center">
  <img src="https://raw.githubusercontent.com/tanjilk/overload/main/img/imgshow.png">
</p>

# 🌙 Instalação:
* Windows:
  * Instala Python 3.8 [aqui](https://www.python.org/downloads/release/python-38)
  * Abre o installer e clica em: `add python to PATH`
  * Faz download do overload
  * Abre o cmd ou o PowerShell no diretório overload
  * Execute este comando: `pip install -r requirements.txt`

* Linux:
  * `sudo apt update`
  * `sudo apt install python3 python3-pip git -y`
  * `git clone https://github.com/7zx/overload`
  * `cd overload/`
  * `pip3 install -r requirements.txt`

* Termux:
  * `pkg update`
  * `pkg install python3 python3-pip git -y`
  * `git clone https://github.com/7zx/overload`
  * `cd overload/`
  * `pip3 install -r requirements.txt`

# :phone: Example SMS & Call flood:
```python3 impulse.py --method SMS --time 20 --threads 15 --target +380123456789```

<p align="center">
  <img src="https://i.ibb.co/KmPnV9f/Impulse-SMS.png">
</p>
