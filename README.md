# Add_To_Server_Lesson

# 🚀 Быстрый старт с Git и GitHub

Этот гайд поможет установить Git, настроить SSH-ключи и начать работать с репозиториями.

---

## 🔧 Обновление системы
```bash
sudo apt update      # Скачать обновления списка пакетов
sudo apt upgrade     # Установить обновления
```

```https://desktop.github.com/download/ - GitHub Desctop```
<br>
apt install git - установка git<br>
ssh-keygen -t ed25519 -C "your_email@example.com" - Создание SSH ключа<br>
eval "$(ssh-agent -s)"<br>
ssh-add ~/.ssh/id_ed25519<br>
cat ~/.ssh/id_ed25519.pub - Получить SSH ключ<br>
<br>
git clone git@github.com:... <br>
<br>
apt install nano - редактор файлов<br>







