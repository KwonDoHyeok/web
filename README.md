# Web

videoTest.html
track 태그를 활용한 동영상 자막 출력 테스트 
Internet Explorer 에서 자막이 표시되도록
web.xml 파일에 mime-mapping 추가
 ```xml
<mime-mapping>
    <extension>vtt</extension>
    <mime-type>text/vtt</mime-type>
</mime-mapping>
