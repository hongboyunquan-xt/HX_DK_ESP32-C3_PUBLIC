# ǰ��
��BLE�����У���ַ��ÿ��BLE�豸���ɻ�ȱ����Ҫ��ɲ��֣���������������ճ���סլ��ַ��ͨ�������ַ�Ϳ����ҵ���ʶ�����BLE�豸�������ܱ���ô��BLE�豸��ȫ�����ˣ���ô��BLE�ĵ�ַ�ַ�Ϊ�ļ����أ�

# ������ַ��Public Address��
BLE�Ĺ�����ַ���������������ճ������֤���룬��ȫ��Ψһ���Ҳ��ɸı�ģ���ͬ���ǣ�
1. Ϊ�˱�֤BLE������ַ��ȫ��Ψһ�ԣ�����Ҫ��[IEEE](https://standards.ieee.org/products-services/regauth/index.html)����Ȼ��IEEE��֯�ͻ��Ӧ�ط��乫����ַ����ң�
1. �����Ҫ��ѯĳBLE�豸�Ĺ�����ַ���ĸ����̵ģ�����Ե��[����](https://regauth.standards.ieee.org/standards-ra-web/pub/view.html#registries)��ѯ����ESP32-C3��ÿ��оƬ���Դ���һ��������ַ��
    <img src="../Asserts/public_address_espressif.png" width = "" height = "" alt="" align=center />

    <img src="../Asserts/public_address_espressif_ieee.png" width = "" height = "" alt="" align=center />

1. ����ȫ��Ψһ������BLE�豸�������������ڣ�������ı䣻
1. �ܳ���Ϊ6���ֽڣ�����ɽṹ����ͼ��ʾ��
    <img src="../Asserts/Public-Address-Format.png" width = "" height = "" alt="" align=center />

    - Company ID��IEEE����ģ������Чλ��
    - Company Assigned����˾�ڲ�����ģ������Чλ��

# �����ַ��Random Address��
���˹�����ַ����֮�⣬����һ�������ַ���ͣ����ַ�Ϊ**��̬��ַ��Static Address��**��**˽�е�ַ��Private Address��**������֮����Ҫͨ����ߵ�2λ��Чλ�����֣�����������ʾ��
## ��̬��ַ��Static Address��
ͬ�������ܳ���Ҳ��48bits��������ߵ�2λ��Чλ��`0b11`����ɽṹ����ͼ��ʾ��

  <img src="../Asserts/static-address-format.drawio.png" width = "" height = "" alt="" align=center />

�õ�ַ���͵���Ҫ�ص����£�
1. ��̬��ַ���������������һ��bit��0��1��
1. �û���������������������£�������������BLE�豸�ľ�̬��ַ��
1. ��̬��ַ���ϵ�֮�󣬲�����;�ı䣻
1. ֻ���������ϵ�֮�󣬲��ܸı侲̬��ַ�����ݣ�
1. ���BLE�豸�ľ�̬��ַ�ı��ˣ���ô����Զ��豸�����֮ǰ�ľ�̬��ַ����ͻᵼ�������ɵĵ�ַʱʧ�ܣ�

## ˽�е�ַ��Private Address��
BLE��˽�е�ַ�ַ�Ϊ**���ɽ���˽�е�ַ��Non-resolvable private address)** �� **�ɽ���˽�е�ַ��Resolvable private address��**������֮�����Ҫ�������£�
### ���ɽ���˽�е�ַ��Non-resolvable private address)

### �ɽ���˽�е�ַ��Resolvable private address��
