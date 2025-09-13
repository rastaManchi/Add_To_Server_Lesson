# 🚀 Быстрый старт с Git и GitHub

Этот гайд поможет установить Git, настроить SSH-ключи и начать работать с репозиториями.

---

## 🔧 Обновление системы
```bash
sudo apt update      # Скачать обновления списка пакетов
sudo apt upgrade     # Установить обновления
```
# Github Desktop
```Links
https://desktop.github.com/download/ - GitHub Desctop
```
# 💻 Установка Git
```bash
apt install git                                     # установка git
ssh-keygen -t ed25519 -C "your_email@example.com"   # Создание SSH ключа
eval "$(ssh-agent -s)"                              # Запуск SSH-агента
ssh-add ~/.ssh/id_ed25519                           # Добавление ключа
cat ~/.ssh/id_ed25519.pub                           # Получить SSH-ключ (для GitHub)
```
# ⬇️ Клонирование репозитория
```bash
git clone git@github.com:username/repository.git
```
# 📝 Установка текстового редактора
```bash
sudo apt install nano
```







