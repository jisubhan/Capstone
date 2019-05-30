
Langur

해당 주제는 모바일 텐서플로우 오픈소스 라이브러리를 활용한 촬영 모듈을 가지는 앱
사물에 대한 인식 및 추론이 가능함에 따라, 해당 사물에 대한 영문 이름을 음성으로 송출하여 영유아로 하여금 영단어 학습을 도와주는 앱

-main.dart-

앱 오른쪽 상단의 AppBar를 이용하여 단일대상을 기본으로 인식을 추천한다.

단일대상을 클릭한 후 인식하고자 하는 대상을 사진촬영

List<PopupMenuEntry<String>> menuEntries = [
                const PopupMenuItem<String>(
                  child: Text('기본'),
                  value: mobile,
                ),
                const PopupMenuItem<String>(
                  child: Text('전체대상'),
                  value: ssd,
                ),
                const PopupMenuItem<String>(
                  child: Text('단일대상'),
                  value: yolo,
                ),

              ];
