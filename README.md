# Android-activity
Скриншоты находятся в папке activity.docx вместе со всеми логами 

При запуске приложения образуется три метода: 
1. onCreate()-метод вызывается при первом создании активности, готовимся показать приложение на экран пользователю.
2. onStart()-метод вызывается при запуске активности, показываем макет пользователю.
4. onResume()- на этом этапе можем взаимодействовать с приложением.
   
После поворота вызываются методы:
1. onPause()-метод вызывается при приостановке активности. Он используется для приостановки любых задач, не можем взаимодействать.
2. onStop()-не видим экран. 
3. onDestroy()-уничтожается полностью приложение, нужно пересоздать.
Затем вызываются  onCreate(), onStart(), onResume() чтобы создать приложение

После того, как мы свернули экран вызываются:
1. onPause()-метод вызывается при приостановке активности. Он используется для приостановки любых задач, не можем взаимодействать.
2. onStop()-не видим экран.
   
Когда откроем приложение снова вызываются:
1. onStart()-метод вызывается при запуске активности, показываем макет пользователю.
2. onResume()-метод вызывается при возобновлении активности. Он используется для возобновления любых задач, пользователь может взаимодействовать.
   
После запуска с finish()
1. Наше приложение сначала создается onCreate()
2. Затем уничтожается onDestroy()   
