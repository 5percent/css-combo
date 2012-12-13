# css-combo

[![Build Status](https://secure.travis-ci.org/daxingplay/css-combo.png)](http://travis-ci.org/daxingplay/css-combo)

## Introduction
combo css which import other css
����js��Ŀǰ�Ѿ��бȽϳ����ģ�黯����������seajs��kissy������css�����أ�һ����ͨ��less���б������ġ�less�ٷ�����less�ļ��е�@import "xxx.css"�ǲ����������ģ���Ҳ�ǿ��ǵ��������������Ҫ��������css���������@import "xxx.less"��less������߾ͻ������Щ�����ģ�飬���д����
css-combo���ǽ��������˼�룬ʵ����cssģ�黯����������ļ���@import����ģ�飬Ȼ�������ļ����д����ʱ�򣬸ù��߻����import���ļ�������Щ�ļ����������

����CSSģ�黯����ӭ��ҿ�����ƪ���ģ�(http://www.techcheng.com/study/css/introduce-css-combo.html)

## Usage

������Ҫnpm��װһ�£�

    npm install -g css-combo

###������ʹ��###

�������£������Ƚ�����Ҫ������ļ�����Ŀ¼��Ȼ��

    csscombo xxx.source.css xxx.combo.css

��һ��������Դ�ļ������ڶ��������Ǵ��֮����ļ���

����ѡ���У�

* -s: silent, ��Ĭģʽ����ʾ������κ���Ϣ
* -ic: inputCharset, ����ָ�������ļ��ı���
* -oc�� outputCharset, ����ָ������ļ��ı���

### ��NodeJS����ʹ�� ###

��Ҳ�������Լ��Ĵ�������е���css combo��������npm��һ����

    var CSSCombo = require('css-combo');
    CSSCombo.build(cfg, function(err){ callback(); });

* cfg ����������������ѡ�

    * target��{String} ����ļ�
    * inputEncoding��{String} �����ļ����룬��ѡ��Ĭ�ϼ������ļ��е�@charset���á��������ļ�û������@charset����ô������ñ�ѡ��
    * outputEncoding��{String} ����ļ����룬��ѡ��Ĭ��UTF-8
    * output��{String} ���Ŀ¼�������������·�������ļ������Ƽ���������ʹ�����·��
    * exclude��{Array} �������������飬��ѡ��Ĭ�Ͽ�
    * compress: {Boolean} �Ƿ�ѹ����Ĭ��Ϊtrue���������ͬYUICompressor
    * debug: {Boolean} �Ƿ��ӡ��־

## TODO

* ����Ŀ¼�����ʽ

## ChangeList

* 0.2.2���������֮������ļ���������

## License
css-combo ���� "MIT"��https://github.com/daxingplay/css-combo/blob/master/LICENSE.md Э��

