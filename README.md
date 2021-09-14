# Получаем и выводим весь список контактов в виде таблицы (console.table)
node index.js --action list
https://monosnap.com/file/MlAWousnWhZQ3QuAIErOjslsU9B1pe
# Получаем контакт по id
node index.js --action get --id 5
https://monosnap.com/file/a9iguFzrwGiQBD98Q3JhtiRXOWevHO
# Добавялем контакт
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/NfoeckQPnXdl5uv8BjHGqHPm0QVuhI
# Удаляем контакт
node index.js --action remove --id=3
https://monosnap.com/file/EVnR1uhfTT5zm5D3AjfgrxWOhnGe7k
