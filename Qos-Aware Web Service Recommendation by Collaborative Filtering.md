### 1 ���
In this paper, we present a collaborative filtering approach for predicting QoS values of Web Services and making Web service recommendation by taking advantages of past usage experiences of users.

������Ҫ����Э�����˵�˼��������QoSֵԤ�����ط����Ƽ������⡣��Ҫ�Ĺ��������¼��㣺

1. ���һ���û�Э���Ļ������ռ���ͬ�û���ͬWeb�������ʷQoS���ݣ�
2. ���һ����ϴ�ͳuser-based��item-based��Эͬ���˷�����Ԥ��Web service��QoSֵ�����ַ�������Ҫ���÷������ͨ�����������û�����ʷQoSֵ������Ԥ�⣻
3. ����ڴ��ģ����ʵ�Ļ����½������飬��֤QoSԤ����������22�����ҵ�100����ʵ����24�����ҵ�150���û���150����QoS���ݱ��ռ���
С�᣺���µ�����һ������Э�����˵�˼��Ӧ�õ�QoSԤ�⣨��ȷ������֮ǰ��û����ʹ���������Ӧ�õ�QoSԤ�⣩���ڶ����ǽ���һ����ʵ��ʵ�����ݼ�������ϵ��������Ϊ������һ���֡�

###2 �û�Э��QoS�����ռ�
���������ռ���ϵͳ����������һƪ���£�Wsrec A Collaborative Filtering Based Web Service Recommender System��

###3 ���ƶȼ���
Pearson Correlation Coefficient ��PCC�� Ƥ��ѷ���ϵ��

�û�a��u�����ƶȼ��㣺

![](QoS-Aware/1.png)

����i��j�����ƶȼ��㣺

![](QoS-Aware/2.png)

##### 3.2 Significance Weighting ��Ҫ��Ȩ��
��Ҫ��Ȩ���Ǳ�����һЩ�û�����񲢲����������ƶ�����ĳЩ�����ķ��������Ƶ�������������û�ʹ�÷���Ľ�������������ͬ�û��Ľ�����*2���Բ��������ɱ������������

�û���Ȩ�����ƶȣ�

![](QoS-Aware/3.png)

�����Ȩ�����ƶȣ�

![](QoS-Aware/4.png)

###4 QoSֵ��Ԥ��

##### 4.1 �����ھӵ�ѡ��
����Ƥ��ѷ���ϵ������õ��Ľ����[-1,1]֮�䣬���ԣ�����ѡ�����ƶȴ���0���ھ���Ϊ�����ھӡ�

#####4.2 ȱʧֵԤ��
UPCC �����û�Э�����˵�QoSԤ�⣺

![](QoS-Aware/5.png)

IPCC ������ƷЭ�����˵�QoSԤ�⣺

![](QoS-Aware/6.png)

��UPCC��IPCC�����һ��

����Ȩ�أ�

![](QoS-Aware/7.png)

![](QoS-Aware/8.png)

user-based��item-based���һ���QoSԤ�⣺

![](QoS-Aware/9.png)

![](QoS-Aware/10.png)

���湫ʽ�õ�һ����Ϊ�걸��UPCC��IPCC��ϵ�ģ�͡�

#####4.3 Ϊ��Ծ�û��ṩQoSֵԤ��
ֵԤ��������Ϊ�û�-�������Ԥ���ֵ�����һ�¡�

#####4.5 ���㸴�Ӷȷ���

###5 ʵ����ʵ��
���������ռ��Ļ�����Planet-lab�Ͻ��У�http://www.planet-lab.org

ʵ�����MAE��ƽ����������RMSE������������ָ��

####�Ա�ʵ��
* ��ǰģ�������Эͬ����QoSԤ��ģ�ͶԱ�:
    1. UMEAN 
    2. IMEAN 
    3. UPCC 
    4. IPCC 
    5. WSRec

* ��ǰģ��������state-of-the-art Э������QoSԤ��ģ�ͶԱ�:
    1. Personalized QoS Prediction(PQP) 
    2. Similarity Fusion(SF)
* ģ�͵��εĶԱ�
    1. Impact of the Missing Value Prediction
    2. Impact of the Significance Weight
    3. Impace of the Cofidence Weight
    4. Impact of Enhanced Top K
    5. Impact of ��
