# FOSS 기말 프로젝트: fwbackups 번역
--------------------------------------

### fwbackups transifex 주소: https://www.transifex.com/Magic/fwbackups/language/ko/ 
  
## fwbackups란? 
---------------
![fwbackups사진](/uploads/dc978e67790dd9fcc30a8652f52a9953/fwbackups사진.png)   
문서를 일회성 또는 반복되는 일정에 따라 백업할 수 있는 기능이 풍부한 사용자 백업 프로그램입니다.  
새 백업을 구성하거나 이전 백업에서 문서를 복원하기 위한 간단한 인터페이스, 여러 백업 형식: 디렉토리 복사 또는 tar 아카이브, SFTP/SSH를 사용하여 원격 호스트에 백업 보내기, 자동 백업 정리, 기존 백업 세트 복원 등의 기능이 있습니다. Linux, OS x, Windows에서 사용 가능합니다.  
fwbackups github 주소: https://github.com/stewartadam/fwbackups  <br/>
  
  
## 주제 선정 이유와 수행 환경
------------------------------
![image](/uploads/44bda2f016b313e51c0bb0caee9769f3/image.png)  
transifex에서 번역 프로젝트 탐색 중 유용하게 사용할 수 있는 Open Source Software 도구인 것 같은데 한국어로 번역한 사람이 아무도 없어 이 프로젝트의 한글 번역에 기여하고자 하였습니다. 번역할 문자열은 523개 였으며, 변역은 transifex가 제공하는 에디터에서 진행하였습니다.

![image](/uploads/c1e09678724f3fcd1a562896345bd07e/image.png)   
Magic team의 한국어 번역자로 제 이름 '장희지'가 추가되었습니다. 
  

## 번역 규칙
------------
1. 가능한 존댓말을 사용하였습니다.
![image](/uploads/97fa515fd21fac6b2c65d1078e883bfa/image.png)  
    
2. please가 붙어 있는 명령어는 모두 해요체를 사용하였습니다.
![image](/uploads/fdb14e3f7402714a67e16515ed2f136e/image.png)  
  
3. ...과 같이 말 줄임표로 끝나고, ing 형식을 쓰는 경우 진행 상황으로 해석하였습니다.
![image](/uploads/08cf2ca940eb2b110751587887606030/image.png)  
  
4. 고유 명사는 영어 그대로 또는 한국어 발음 대로 변역하였습니다.
![image](/uploads/bf1949e67196df4395a0109df3bcbe86/image.png)  
![image](/uploads/1a18119d6380e55b916474f238487478/image.png)  
  
5. 원본 형식을 유지하면서 번역하려고 노력했고, 문자 중간에 _표시가 들어가는 경우가 많아 이 형식을 유지하면서 한국어로 표현할 수 없었을 때 생략하였습니다.
![image](/uploads/70c0102b44dcac0f96a3cbf46fcf9879/image.png)  
![image](/uploads/f535f1f2410ec8f842520b5426f95ae9/image.png)  
  
6. 영어는 수의 개념을 중요히 여기기 때문에 명사의 단복수를 정확히 구분합니다. 하지만, 한국어는 그렇지 않은 부분이 많아 거의 단수로 해석하였습니다.  
![image](/uploads/8ed5b1a9babd1010cd6ad23c33dbd9ad/image.png)  
위 사진은 괄호를 넣지 않아서 주의가 떳는데 시간(들), 분(들) 이렇게 복수로 표현하기에는 어색한 감이 있어서 단수로 표현했습니다.  
  

## 번역 용어 정리
----------------- 
자주 나오는 용어에 대해서 간단하게 정리를 해보았습니다.  
* 구성 세트(Configuration sets)  
    구성 세트는 확인된 ID에 적용할 수 있는 규칙 그룹입니다.     

* 구성 파일(Configuration File)    
    구성 파일은 웹 서버나 웹 응용 프로그램에 대한 구성정보가 들어 있는 .config 확장자를 가진 XML파일입니다.  

* 백업(backup)  
    백업은 임시 보관을 일컫는 말로, 데이터를 미리 임시로 복제하여, 문제가 일어나도 데이터를 복구할 수 있도록 준비해 두는 것입니다.    

* 증분 백업(incremental backup)
    증분 백업은 일정 시간마다 변경된 데이터만 백업하는 방식입니다. 다른 백업보다 복구시간이 오래걸리는 단점이 있지만 파일 양이 적어 빠른 백업이 가능한 장점이  있습니다.

* 일회성 백업(one-time backup)  
    크론탭을 사용하여 반복적인 일정에 따라 수행하는 백업이 아닌 일반적인 백업을 말합니다.  

* 크론탭(crontab)  
    개별 사용자에 대한 crontab 파일을 유지 관리합니다. 스케줄러와 같이 예약한 시간에 특정 작업을 수행할 수 있습니다.   

* 나이스 값(Nice value)  
    리눅스 명령어인 nice는 프로세스의 우선 순위를 변경하는 기능을 합니다. 나이스 값의 범위는 -20부터 19까지인데 값이 낮아야 우선순위가 높으므로, 가장 높은 우선 순위는 -20입니다.  

* 트레이(tray)
    시스템 트레이는 작업표시줄에 시계와 몇몇 프로그램들의 아이콘을 나타냅니다. 시스템 트레이는 윈도우95/98/NT에서 작업표시줄의 한쪽 끝에(대개 우측 하단에) 위치해 있는 부분을 말합니다. 
  

## 기억에 남았던 문자열 번역
----------------------------
![image](/uploads/c65e00ca9e92e292b56c0f4578ffb0c5/image.png)  
위 사진의 문자열 번역을 통해 fwbackups는 오픈 소스 라이선스 중 GPL을 사용했음을 알 수 있었습니다. 수업 시간에 배운 내용을 번역 도중 만나게 되어 인상 깊었습니다.  


## 느낀점
---------
평소에 외국 사이트를 한국어로 번역한 것을 읽을 때 어색한 표현 땜에 헷갈렸던 적이 있습니다. 제가 번역한 소프트웨어는 이런 느낌을 주지 않기 위해서 최대한 자연스럽게 해석하려고 노력했지만 부족한 부분도 있는 것 같습니다. 오픈 소스 프로젝트를 각기 다른 말로 번역해주는 사이트가 있다는 것도 이번 프로젝트를 통해 알게 되었습니다. 프로젝트를 통해 crontab과 다양한 backup 기법들 등 프로젝트 관련 용어들을 익히게 되었고, 이 소프트웨어를 제가 번역한 버전으로 사용한다면 매우 뿌듯할 것 같습니다. 오픈 소스 코드에 조금이나마 기여를 할 수 있어 뜻 깊은 경험이었습니다.  
  
  
## 참고 문헌
-------------
위키 백과, 백업, (검색일: 2022.6.25), <https://ko.wikipedia.org/wiki/%EB%B0%B1%EC%97%85>.  
혼자공부하기:티스토리, 증분 백업, (검색일: 2022.6.25), <https://noil0816.tistory.com/109>.   
티스토리, 나이스 값, (검색일: 2022.6.25), <https://jhnyang.tistory.com/394https://jhnyang.tistory.com/394>.   
시스템 트레이, <http://www.terms.co.kr/systemtray.htm>.

