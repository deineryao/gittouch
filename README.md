linux command
 
$ mkdir xx //�����ļ���
$ pwd //��ʾ��ǰĿ¼
$ touch xx.txt //�����ļ���
$ rm -rf xx //ɾ���ļ���
$ rm -f xx.txt //ɾ���ļ�

git command

git log //�鿴�ύ��ʷ
git diff xx //�鿴�����ύ/��֧/�ļ����� �Ķ������δ�ύҲ�ɶԱȸĶ��仯
git reset --hard HEAD^ //���˵��ϸ��汾
git reset --hard c9cec01 //���˵�ָ���汾��ͨ��git log ��ȡ�汾idǰ7λ��
git reflog //��¼ÿһ����������ҵ�ɾ���İ汾

�����Ϊ����
1.�޸�֮��δadd
ֱ��ʹ��git checkout -- readme.txt(�������������޸�)
2.�޸�֮��add��
��git reset -- HEAD .txt(�����ݴ������޸�)
��git checkout -- readme.txt(�������������޸�)
3.commit֮��
git reset -- hard HEAD^�汾����


�鿴��֧��git branch
������֧��git branch <name>
�л���֧��git checkout <name>
����+�л���֧��git checkout -b <name>
�ϲ�ĳ��֧����ǰ��֧��git merge <name>
ɾ����֧��git branch -d <name>