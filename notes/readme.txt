1��������ϵ

config/dev.evn.js��config/prod.evn.js------��������config/index.js

config/prod.evn.js-------->������config/dev.evn.js

2��Vueѧϰ�ʼ�   http://blog.csdn.net/chang_yuan_2011

3��vuex�����ڴ��͵���Ŀ

4����package.json�ķ���
     
    "name": ��Ŀ��,
    "version": �汾,
    "description": ����,
    "author": ����,
    "private": privateΪtrue��npm��ܾ�������
    "scripts": ����ű����npm run dev�ȼ���node build/dev-server.js
{
    "dev": "node build/dev-server.js",
    "build": "node build/build.js"
 },
    "dependencies":   ����������������������������npm i node_module �CS,���Լ�����ʹ�ã�
    "devDependencies":�ڿ�������������������������npm i node_module �CD,�������ṩ����
    "engines": ָʾ��ǰ��������node&npm�汾 
{
    "node": ">= 4.0.0",
    "npm": ">= 3.0.0"
 }

5