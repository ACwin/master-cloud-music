# master-cloud-music
# ΢��С����-����������App

> Vue+Nodejs ������������ Android �ͻ���ʵս ΢��С����汾


## ? ����

����ģ�飺
- [x] �ֲ�ͼ
- [x] �Ƽ��赥
- [x] ���а�
- [x] ÿ���Ƽ�����

��Ƶ & ����ģ�飺

- [ ] �Ƽ�MV
- [x] ��ȡ�Ƽ���Ƶ & ����
- [ ] ��Ƶ&���� ���� ���� �ظ�
- [x] ����ͼƬ��ʾ
- [x] �����л�Ч��
- [ ] �赥����
- [ ] �������
- [ ] ���Ž��������Ի�

������Ϣ��

- [x] �ֻ���¼
- [ ] �����¼
- [x] ͷ�� �˻���Ϣ ����ȡ
- [x] ������Ÿ���

����ģ�飺

- [x] �����б�
- [x] ����Ĭ�Ϲؼ���
- [ ] ��������ƥ��




- ��װ 

  ```
  $ git clone https://github.com/ACwin/master-cloud-music.git
- ���� `cd �� netease_api`

  ```
  $ node app.js
- ʹ��˵��

  - ��ĿĿ¼�ṹ

    ```html
    mo_music                        // ĭ����
    ������ components                  // ���
    ������ netease_api        		    // Node�汾���������ֽӿ�
    ������ pages                       // С����ҳ��
    ��       ������ index                 // ��ҳ
    ��       ������ login                 // ��¼ҳ
    ��       ������ personal              // ��������
    ��       ������ recommendSong         // ÿ���Ƽ�
    ��       ������ search                // ����ҳ
    ��       ������ songDetail            // ������ϸҳ
    ��       ������ video                 // ��Ƶҳ
    ������ utils                       // ����
    ��       ������ request.js            // �����װ��
    ������ static                      // ��̬��Դ/ͼƬ
    ```
    
    - ��Ҫ NodeJS 8.12+ ����
    - ��װ ΢��С���򿪷��߹��� ���°� 
    - ��Ŀ����� ��ѡ΢�ſ���������Ӧ����
      - ES6 ת ES5
      - ��ǿ����
      - ʹ��npmģ��
      - ��У��Ϸ�������web-view(ҵ������)��TLS�汾�Լ� HTTPS ֤��

  ### ����ջ
  - ΢��ԭ��С���򿪷�
  - WX��� & API: ʹ��ԭ���ܹ�����
  - ajax������http����
  - ES6������ES6�﷨��
  - HTML5: ��Ŀ����ṹ�
  - JavaScript: ����ҳ��Ϊ���б��
  - CSS3��CSS3��������ʽ��

## ?? ���ÿ�������

����Ŀ�� [NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) �ṩ API���Ѿ������ڱ���Ŀ��`netease_api`Ŀ¼

### ������ Vercel

1. ���������� API������μ� [Binaryify/NeteaseCloudMusicApi](https://neteasecloudmusicapi.vercel.app/#/?id=��װ) ����Ҳ���Խ� API ���� `Vercel`
2. ������ֿ����Ͻǵ� Fork�����Ʊ��ֿ⵽��� GitHub �˺�
3. �� [Vercel.com](https://vercel.com/)��ʹ�� GitHub ��¼
4. ��� `Import Git Repository` ��ѡ����ոո��ƵĲֿⲢ��� `Import`
5. ��� `PERSONAL ACCOUNT` �Աߵ� `Select`
6. ��� `Environment Variables`����д Name Ϊ `VUE_APP_NETEASE_API_URL`��`Value` Ϊ��ող���������� API ��ַ����� Add��������ײ��� Deploy �Ϳ��Բ��� Vercel ��

## ??  ��Դ���
����Ŀ��������ѧϰ�о�ʹ�ã���ֹ������ҵ���Ƿ���;��


## ??? ��ͼ