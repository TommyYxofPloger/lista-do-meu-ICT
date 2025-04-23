# <img src="https://i.imgur.com/ZgbpGWM.png" alt="ICT Lab Logo" width="120"/> Laboratório de Manutenção ICT – Kit de Ferramentas para Linux</p>

Este repositório contém uma seleção essencial de ferramentas para diagnóstico, manutenção, recuperação e otimização de sistemas Linux, cobrindo as cinco distribuições mais populares: **Ubuntu**, **Debian**, **Fedora**, **Arch Linux** e **openSUSE**.

---

## 🔧 Diagnóstico de Sistema

**Neofetch / Screenfetch** – Exibe informações básicas do sistema com estilo.  
`sudo apt install neofetch` / `sudo dnf install neofetch` / `sudo pacman -S neofetch`

**inxi** – Diagnóstico detalhado de hardware e sistema.  
`sudo apt install inxi` / `sudo zypper install inxi`

**lshw** – Lista hardware detalhado.  
`sudo lshw`

**htop** – Monitor interativo de processos.  
`sudo apt install htop`

**nvtop** – Monitoramento de GPU Nvidia.  
`sudo apt install nvtop`

---

## 💿 Disco e Partição

**GParted** – Gerenciador de partições gráfico.  
`sudo apt install gparted`

**GNOME Disks (gnome-disk-utility)** – Gerenciamento e benchmark de discos.  
`sudo apt install gnome-disk-utility`

**smartmontools** – Monitoramento S.M.A.R.T. de discos.  
`sudo apt install smartmontools`

**badblocks** – Checagem de blocos defeituosos.  
`sudo badblocks -sv /dev/sdX`

---

## 📂 Backup e Clonagem

**Timeshift** – Backup e restauração do sistema.  
`sudo apt install timeshift`

**Clonezilla** – Clonagem de discos e partições.  
Disponível via Live USB – https://clonezilla.org

**rsync** – Sincronização de arquivos e backups.  
`rsync -avh /origem /destino`

**Déjà Dup** – Backup gráfico para GNOME.  
`sudo apt install deja-dup`

---

## 🔍 Antivírus & Antimalware

**ClamAV** – Antivírus open-source.  
`sudo apt install clamav`  
`sudo freshclam && clamscan -r /home`

**Chkrootkit** – Verificação de rootkits.  
`sudo apt install chkrootkit`

**rkhunter** – Hunter de rootkits.  
`sudo apt install rkhunter`

---

## 🔑 Recuperação de Senhas

**chntpw** – Edita registros do Windows para reset de senhas.  
`sudo apt install chntpw`

**John the Ripper** – Quebra de senhas (uso avançado).  
`sudo apt install john`

---

## ⚙️ Otimização e Limpeza

**BleachBit** – Limpeza geral do sistema.  
`sudo apt install bleachbit`

**Stacer** – Otimização e monitoramento com GUI.  
https://github.com/oguzhaninan/Stacer

**Preload** – Melhora o desempenho carregando apps usados com frequência.  
`sudo apt install preload`

---

## 🌐 Rede

**nmap** – Escaneamento de redes.  
`sudo apt install nmap`

**Wireshark** – Analisador de pacotes.  
`sudo apt install wireshark`

**iperf3** – Medição de largura de banda.  
`sudo apt install iperf3`

**NetTools** – ifconfig, netstat, etc.  
`sudo apt install net-tools`

**nmcli** – Gerenciamento de redes via linha de comando.  
Já incluído com NetworkManager.

---

## 🛠️ Utilitários Gerais

**Etcher** – Criação de pendrives bootáveis.  
https://www.balena.io/etcher/

**KDiskMark** – Benchmark de disco (GUI).  
`sudo flatpak install flathub io.github.jdah.KDiskMark`

**GNOME System Monitor / KDE KSysGuard** – Monitoramento de sistema.  
Já incluídos em distros GNOME/KDE.

**AppImageLauncher** – Facilita execução de AppImages.  
https://github.com/TheAssassin/AppImageLauncher

---

> Última atualização: abril de 2025  
> Criado por: Tommy para o Laboratório ICT – versão Linux  
> Suporte multiplataforma? Esse laboratório voa! 🛠️🐧⚡