# Markdown ����

### �ζ��� �ڵ��
> `inline code`
`inline code`

### ���ڿ�
> *����̱�*
> **���� ���ڿ�**
> ~~��Ҽ�~~
> <u>����</u>

*����̱�*
**���� ���ڿ�**
~~��Ҽ�~~
<u>����</u>

### ����Ʈ
> * ����Ʈ1
> * ����Ʈ2
>   * ����Ʈ2-1
>     * ����Ʈ2-1-1
> * ����Ʈ3

* ����Ʈ1
* ����Ʈ2
  * ����Ʈ2-1
    * ����Ʈ2-1-1
* ����Ʈ3

### ���� ����Ʈ
> 1. ���� ����Ʈ1
> 2. ���� ����Ʈ2

1. ���� ����Ʈ1
2. ���� ����Ʈ2


### �̹���
> ![Markdown Here logo](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon24.png)
> [��ũ](http://sonim1.tistory.com)

![Markdown Here logo](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon24.png) 
[��ũ](http://sonim1.tistory.com)

### �ο빮
> �ο빮. 
>>��ø
>>>����ø1
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
> | �ѱ� | ���� | ���� |
> | ------------- |:-------------:| -----:|
> | ������ | 77 | aa|
> | �� | 88 | bb |
> | �� | 99 | cc |

| �ѱ� | ���� | ���� |
| ------------- |:-------------:| -----:|
| ������ | 77 | aa|
| �� | 88 | bb |
| �� | 99 | cc |

### url��ũ
> [1]: https://naver.com
> [NAVER](https://naver.com "���̹�.")
> [GitHub][1]

[1]: https://naver.com
[NAVER](https://naver.com "���̹�.")
[GitHub][1]


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
