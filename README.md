# 布署你的開發環境

## 1. 使用我們設定好的VirtualBox
### a. Google Drive
- https://drive.google.com/drive/folders/1LbSv4U3Q2M-KiFXZMa5NezVZr4TO6bP2?usp=sharing
- 使用者帳號: `user`
- 使用者密碼: `0000`

### b. GitHub Release
- https://github.com/easy-ebpf/practice_vm/releases/latest
- 使用者帳號: `ubuntu`
- 使用者密碼: `ubuntu`
- 下載所有zip檔之後解壓就可以得到一個ova檔，再進行匯入即可。
<details>
    <summary>
    映像檔匯入VirtualBox教學(點我展開)
    </summary>
        
![image](https://github.com/user-attachments/assets/5bed1f9a-7d38-4890-855e-1d3792c8d68e)
![image](https://github.com/user-attachments/assets/4f9e7518-0bd6-403c-bbef-208d5316002a)
![image](https://github.com/user-attachments/assets/7bccc8b6-c7d6-4677-87ea-b0267cedb161)
![image](https://github.com/user-attachments/assets/8168913a-6063-4afc-94ec-dcbae7484ccc)
![image](https://github.com/user-attachments/assets/d8780cfe-1cde-4f2d-9544-c94588204d2b)
</details>


## 2. 使用自己的Ubuntu
- `sudo apt install -y bpftool libbpf-dev build-essential clang`
