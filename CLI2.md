# CLI 2

## I/O Redirection, Expansion, Backslash

- Standard Output (default : screen)
    - **>**:다른 곳으로 output 출력 가능.
        - cat으로 해당 text file의 내용 출력.
        
        ![image.png](image%2012.png)
        
    - **>>**:기존 file 내용 뒤에 추가.
        
        ![image.png](image%2013.png)
        
- Standard Input
    - **sort < words.txt** (words.txt를 정렬한 것을)
    - **>sorted_words.txt** (에 저장)
    
    ![image.png](image%2014.png)
    
- Expansion : echo (*, ~)
    
    ![image.png](image%2015.png)
    
- Tip : Backslash
    
    ![image.png](image%2016.png)
    

---

## Permission, Superuser

Linux는 multi-user system 임 ⇒ Owner, Group, Others로 나뉨.

![image.png](image%2017.png)

- Changing Permissions
    
    ![image.png](image%2018.png)
    
    ![image.png](image%2019.png)
    
- Superuser
    
    ![image.png](image%2020.png)
    

---

## Text Editors, Shell Script, History

- Text Editors (키보드로만 문서 작업)
    
    Linux에서, CLI-based or GUI-based text editors 존재.
    
    - Command line
        - vi, vim
        - Emacs
        - nano
    - Graphical
        - gedit
        - kwrite
- Shell Script
    
    Write and run a shell script
    
    ![현재 작업 중인 directory에 해당 file이 없으면 새롭게 만듦.](image%2021.png)
    
    현재 작업 중인 directory에 해당 file이 없으면 새롭게 만듦.
    
- Tip : History
    
    ![image.png](image%2022.png)
    

---

## wget, curl, grep

- wget
    
    현재 작업중인 directory로 파일 다운.
    
    ![image.png](image%2023.png)
    
- curl
    
    fetching, uploading, and managing data over the Internet
    
    ![image.png](image%2024.png)
    
- grep
    
    ![image.png](image%2025.png)
    
