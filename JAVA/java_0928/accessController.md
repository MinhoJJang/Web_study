# ����������

- ���������� : �ܺο��� �������� ���ϵ��� �����ϴ� ������ �Ѵ�. 

- ���������ڴ� Ŭ����. �������, �޼���, ������ �տ� �ٴ´�.

private - ���� Ŭ���� ����
(default) - ���� ��Ű�� ��
protected - ���� ��Ű�� ������, �ٸ� ��Ű���� �ڼ� Ŭ������ ���� ����
public �������Ѿ���

```java
public > protected > default > private 
```

Ŭ������ public, default 
�޼���, ������� - public protected default private
�������� - ���� 

**Ŭ������ ���, �ַ� ����� ���� �����ڸ� ����ϴ� ������ Ŭ���� ������ ����� �����͸� ��ȣ�ϱ� ���ؼ��̴�. �����Ͱ� ��ȿ�� ���� �����ϰ� �ϰų�, ��й�ȣ�� ���� �߿��� �����͸� �ܺο��� �Ժη� �������� ���ϰ� �ܺηκ����� ������ �����ϴ� ���� �ʿ��ϴ�.**

# ĸ��ȭ

**�ܺο��� ������ �ʿ䰡 ���� ������� private�� �����Ͽ� �ܺο� ������ �������� ���⼺�� ���� �� �ִ�. (ĸ��ȭ)**

```java
public class Time { // public 

    public int hour;
    public int minute;
    public int second;
}
```

�̷��� ���� public ���������ڰ� �����Ǿ� ������

```java
    Time t = new Time();
    t.hour = 25; -> �̷��� �ٲ���� �� ����... 
```

���� private ���������ڸ� �̿��ؼ� ��������� �����ϰ�, �� ��������� �а� ������ �� �ִ� getter, setter�� public���� �����Ͽ� ���������� �ٲ� �� �ֵ��� �ؾ� �Ѵ�. 