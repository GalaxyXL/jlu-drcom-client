---------------
### Simple JLU drcom client dirty hack C-version

��Ҫ�޸� drcom.c �ļ��� user(�ʺ�), pass(����), mac(MAC ��ַ, 0x010203040506 ��ʽ) �Ȳ���������
	
	gcc drcom.c md5.c -o drcom


ֱ�����ն����� ./drcom 

haha, dirty hack ����ˬ (������)��

��Ϊ�� daemon ��ʽ���У�ȥ�� long ���ͣ�֧�� 32 λϵͳ

TODO: logout
