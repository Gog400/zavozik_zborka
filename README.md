<details>

<summary> Описание сборки </summary>

Minecraft 1.20.1\
Java 17\
Forge ModLoader 47.4.0\
Рекоммендуемое кол-во памяти: 4-6 GB (на 4гб сборке может не хватать памяти для загрузки миров).\

</details>

<details>
  
<summary> Как начать играть? </summary>

### Установка лаунчера

1) Заходим с ВПНом и качаем лаунчер:
https://prismlauncher.org/download/windows/

2) Устанавливаем и закрываем лаунчер

3) Качаем файл accounts.json и добавляем его с заменой в %appdata%/PrismLauncher/

4) Создаем свой оффлайн аккаунт и делаем его дефлотным (No profile Xbox profile missing не удалять!):
![telegram-cloud-photo-size-2-5343725991480129983-y](https://github.com/user-attachments/assets/ef65df7b-bbd6-41a7-889f-a025319dba48)

5) Качаем архив со сборкой и добавляем в лаунчер
![telegram-cloud-photo-size-2-5341474191666444065-y](https://github.com/user-attachments/assets/6bec3fba-a0d7-4624-999a-53e76a030839) 

6) Заходим. 

</details>

<details>
  
<summary> Скачать сборку </summary>

### Яндекс Диск
https://disk.yandex.ru/d/FXOIXUK9qUVEgQ 

</details>

<details>
  
<summary> Как выделить память? </summary>

### Выделение памяти в лаунчере
<img width="2754" height="1566" alt="image" src="https://github.com/user-attachments/assets/14208f54-b660-4fca-9978-d665c0fc8505" />

### Настройки запуска Java(по умолчанию не нужно, можно попробовать если лагает)

`-XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=40 -XX:G1MaxNewSizePercent=50 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=20 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 `

</details>



