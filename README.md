Благојче Димов
216089

![A](https://github.com/Baze-cmd/SI_2023_lab2_216089/blob/master/cfg.jpg)

Со броење на регионите на графот цикломската комплексност следи дека е 11

Тест случај 1: user == null, user.username == null, user.password == "1", user.email == "a"
Тест случај 2: user != null, user.username == "u", user.password == "1", user.email == "@.", allUsers.size()>1, existingUser.email == "@.", existingUser.username == "u"
Тест случај 3: user != null, user.username == "u", user.password == "1", user.email == "@.", allUsers.size()>1, existingUser.email == "a", existingUser.username == "a"
Тест случај 4: user != null, user.username == "u", user.password == "1", user.email == "@.", allUsers.size() == 0
Тест случај 5: user != null, user.username == "u", user.password == "1", user.email == "@."
Тест случај 6: user != null, user.username == "u", user.password == "123456789!", user.email == "@."
Тест случај 6: user != null, user.username == "u", user.password == "123456789", user.email == "@."


За if (user==null || user.getPassword()==null || user.getEmail()==null)
Тест случај 1: user == null, условот се евалуира во true без разлика на останатите
Тест случај 2: user != null, user.password == null, условот се евалуира во true вез разлика на user.email
Тест случај 3: user != null, user.password == "p", user.email == null, условот се евалуира во true
Тест случај 4: user != null, user.password == "p", user.email == "e", условот се евалуира во false
