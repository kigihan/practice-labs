_供 WMI Fileless Backdoor Lab 練習參考文件_ 

_by Han.Chen_

分為幾份參考文件，概要如下：
- [1.start_lab_and_pwn_it.md](./1.start_lab_and_pwn_it.md)
  - VirtualBox 啟動受害虛擬機
  - 準備攻擊環境
  - 受害虛擬機往攻擊環境建立 reverse shell
  - 開心打
- [2.live_forensic.md](./2.live_forensic.md)
  - Live Disk Forensic
    - Process Explorer
    - TCPView
    - Autoruns
    - Event Viewer
- [3.memory_forensic.md](./3.memory_forensic.md)
  - Memory Forensic
    - Process Explorer: Volatility3: pstree
    - TCPView: Volatility3: netscan
    - Autoruns: Volatility3: filescan, dumpfiles
      - 其他跟 Autoruns 相關的可能有 driverscan, envars, registry.hivelist, registry.hivescan, svcscan
    - Event Viewer: EVTXtract
    - Volatility3: memmap
    - Volatility3: malfind
