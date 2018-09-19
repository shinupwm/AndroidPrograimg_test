# Markdown ����

### �ζ��� �ڵ��& �ٹٲ�
> `<br>inline code`
<br>`inline code`

### ���ڿ�
> `*����̱�*`<br>
> "**���� ���ڿ�**`<br>
> `~~��Ҽ�~~`<br>
> `<u>����</u>`

*����̱�*<br>
**���� ���ڿ�**<br>
~~��Ҽ�~~<br>
<u>����</u>

### ����Ʈ
> `* ����Ʈ1`<br>
> `* ����Ʈ2`<br>
> `  * ����Ʈ2-1`<br>
> `    * ����Ʈ2-1-1`<br>
> `* ����Ʈ3`

* ����Ʈ1
* ����Ʈ2
  * ����Ʈ2-1
    * ����Ʈ2-1-1
* ����Ʈ3

### ���� ����Ʈ
> `1. ���� ����Ʈ1`<br>
> `2. ���� ����Ʈ2`

1. ���� ����Ʈ1
2. ���� ����Ʈ2


### �̹���
> `![Markdown Here logo](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon24.png)`
> `[��ũ](http://sonim1.tistory.com)`

![Markdown Here logo](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon24.png) 
[��ũ](http://sonim1.tistory.com)

### �ο빮
> �ο빮. 
>>��ø
>>>����ø1<br>
>>>����ø2
 
### ���
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

### ���м�
---

### ���̺�
> `| �ѱ� | ���� | ���� |`<br>
> `| ------------- |:-------------:| -----:|`<br>
> `| ������ | 77 | aa|`<br>
> `| �� | 88 | bb |`<br>
> `| �� | 99 | cc |`<br>

| �ѱ� | ���� | ���� |
| ------------- |:-------------:| -----:|
| ������ | 77 | aa|
| �� | 88 | bb |
| �� | 99 | cc |

### url��ũ
> `[1]: https://naver.com`<br>
> `[NAVER](https://naver.com "���̹�.")`<br>
> `[ù��°][1]`<br>

[1]: https://naver.com<br>
[NAVER](https://naver.com "���̹�.")<br>
[ù��°][1]<br>


# git ��ɾ�


### ���� ���� ���� ��ȸ
>  git config - -global - -list

### ���� ���� ���� ������Ű��
> git config --global --unset-all user.email

> git config --global --unset-all user.name




### ���ο� ����� �ʱ�ȭ�ϱ�
> git init

### ����� �����ϱ�
>  git clone <����� url>

### ���ο� ���� ����� �߰��ϱ�
>  git remote add <���� �����> <����� url>

### ���ο� ���� git�� ��Ͻ�Ű��(staging)
> git add <����>

### ������� �۾��� ���� �����ϱ�

> git commit -m ��<�޽���>��


### ���� ����ҿ��� ��ġ�� �ʰ� ���� �귣ġ�� ���� ���� ��������
> git fetch <���� �����>

### ���� ����ҿ��� ���� ������ ������ ���� �귣ġ�� ��ġ��
> git pull <���� �����>

### ���ο� ���� �귣ġ�� ���� ����ҿ� Ǫ���ϱ�
> git push <���� �����> <���� �귣ġ>

### ����� �ڵ��� ���¸� Ȯ���� �� �ִ� ��ɾ�
> git status

### git add�� ���� ������Ʈ�� �귣ġ�� ���������� �ƴϸ� ����ڵ��� ����� ���� �귣ġ ������ �˷��ش�
> git branch

### �������� ���� �귣ġ�� ���� ���� �귣ġ, �Ǵ� ������ ��� �귣ġ�� ����Ī�Ҽ� �ִ�.
> git checkout

### ���ݱ����� ���� ������ ���� �ش� �귣ġ�� ����
> git merge

### ���� �ֱٿ� Ŀ���ߴ� ������ �ҷ���
> git reset --hard
