# MYVIM
## Ŀ¼
- [����](#����)
- [��װ](#��װ)
- [����](#����)
- [����](#����)
- [������������](#������������)

## ����
����һ���Ҹ�����ƫ�õ�VIM���ã���������ݰ�����
- ����
- ƫ������
- ���

## ��װ
���Ƚ�clone�����������ʵ�Ŀ¼��.
```bash
git clone https://github.com/Ge0rgeCai/MYVIM.git
Or Use "Github CLI"
gh repo clone Ge0rgeCai/MYVIM
```
��vim��ʹ��`.vimrc`�������ļ�
��gvim��ʹ��`_vimrc`�������ļ�
## ����
- [vim-plug](https://github.com/junegunn/vim-plug) ���������
- [coc.nvim](https://github.com/neoclide/coc.nvim) �����Զ���ȫ���
## ����
### Hosts
�������ذ�װ `vim-plug` ʱ�����ܻᰲװʧ�ܡ�
������� `hosts` �����⣬�����ͨ���޸� `hosts` �ļ������������⡣
�������Ĵ������� `hosts` �ļ��ڡ�

```
199.232.28.133 raw.githubusercontent.com
```
### ��λ�޸�(��ѡ)
��vim����Ϊ����ʹ��`<ESC>`,�����Ҹ�Ը�⽫`<Caps_Lock>`��`<ESC>`��λ���н���<br/>
1. **Windows**:<br/>
��Windows����Ҫ��ͨ��ע�����м�λ�����ġ�
- �����д��뱣��Ϊcaps.reg�ļ������м��ɡ�
```
Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout]
"Scancode Map"=hex:00,00,00,00,00,00,00,00,03,00,00,00,01,00,3a,00,3a,00,01,00,00,00,00,00
```
- ͨ��ע���༭���ֶ����
`Win`+`R`-->����regedit-->�ҵ�`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout`
-->�Ҽ�`Keyboard Layout`-->"�½�"-->"������ֵ"-->������"��ֵ#1"Ϊ`"Scancode Map"`-->�Ҽ�"Scancode Map"
-->"�޸�"-->����ֵ����:
```
0000 00 00 00 00 00 00 00 00
0008 03 00 00 00 01 00 3a 00
0010 3a 00 01 00 00 00 00 00
0018
```
2. **Linux**:<br/>
Linux�û�����ͨ������һ��`keys.conf`�ļ�������ʹ��`loadkeys keys.conf`�������ı�linux������������ת�����������̡�
#keys.conf�ļ�����
```
keycode 1 = Caps_Lock
keycode 58 = Escape
```
�����ַ�����һЩ���滷�����޷���Ч������ķ��������������ҡ�
## ������������
 ���⣺<br/>
 [vim-one](https://github.com/rakr/vim-one)<br/>
 [molokai](https://github.com/tomasr/molokai)
