# ROS_STM32F1
## ����STM32F1ƽ̨��ROS�����˵��̿��Ƴ���

### ʹ�÷���
1. ͨ��usbת����ģ�����ӵ�STM32F1ƽ̨��USART3���ڣ������ڳ���������Ϊ�������ڣ����Ѱ�װ��ros��Ubuntuϵͳ�ĵ��ԡ�
2. �����նˣ�����roscore �س���
3. ������һ���նˣ�����rosrun rosserial_python serial_node.py /dev/ttyUSB0 _baud:=57600 �س� �����Ϻ��ն˻��ӡ���ӳɹ�����Ϣ��
4. ������һ���նˣ�����rostopic list ���Ի�ȡ��ǰ��topic��Ϣ������rostopic echo /odom �س� ���Ի�ȡ�����ϴ���odom���ݡ�
