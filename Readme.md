1- İlk olarak kurulumlar yapıldı. Express.js ,sequelize ,mysql2, body-parser, cors jsonwebtoken bcryptjs


2-Server.js üzerinde web sunucusu kuruldu.
  -Ekspres, Rest API'leri oluşturmak içindir
  -body-parser , isteği ayrıştırmaya ve req.bodynesneyi oluşturmaya yardımcı olur
  -cors , CORS'u etkinleştirmek için Express ara yazılım sağlar.
 
3- db.config dosası hazırlandı 

4-user.model.js ve role.model.js hazrılandı.Bu modeller veritabanınında kullanıcı ve rolleri temsil eder.

5-models/index.js oluşturularak kullanıcı ve roller arasındaki ilişki belirlendi . Çoktan çoğa ilişki ( birden fazla kullanıcı birden fazla role sahip olabilir.Bir Rol, birçok Kullanıcı tarafından kullanılabilir.)

6-server.js sync() methodu çağırlarak güncellemeler yapıldı.
