# Proficiency level

Una consultora cárnica 🍖 ha abierto unas nuevas oficinas en Barcelona para atraer a las empresas del sector IT y conseguir contratos. Las nuevas oficinas tienen una capacidad de 200 empleadas que en ningún concepto se pueden superar ya que es muy difícil engañar a las inspecciones de trabajo 🕵 con este tema.
Han decidido ir en busca de incautos y han fichado a 50 frontends, 100 fullstack y 50 backends.

Una vez contratadas tienen que decidir en qué proyecto quieren invertir esos developers. El proyecto es a precio cerrado y el coste por developer no varía, independientemente de las horas que vayan a hacer. Para saber el precio que cada empresa está dispuesta a pagar por perfil en ese proyecto 💰 se conectan a una bolsa de proyectos. El enlace del servicio es [este](https://raw.githubusercontent.com/Trepix/Kata-Carnica/master/statements/data/projects-proficiency.json). 

En esta borsa puede ser que encuentren proyectos que no pueden hacer o porqué no tienen los perfiles que solicitan o porqué no tienen suficientes developers con esas habilidades. Además, se pueden encontrar precios en diferentes divisas. Para hacer la conversión a euros la empresa aún no ha decidido que sistema va a usar pero por el momento esta [API](https://exchangeratesapi.io/) les parece suficiente.

Aunque el proyecto es a precio cerrado, los proyectos se tienen que entregar completos por contrato por lo que las developers tendrán que hacer extras ⏳. Para saber el número de horas usan sus experiencias pasadas y en función del sector al cual pertenece el proyecto estiman un número de horas:

* Empresa eléctrica : 800 horas extras
* Instituciones Públicas : 1100 horas extras
* Banca : 600 horas extras
* Otros : 900 horas extras

Para que los developers no se alcen y se queden al menos hasta que termine el proyecto han calculado que tendrán que pagar 2€ por hora extra en cafés ☕️.

Finalmente la consultora ha estimado que debido a los retrasos los clientes se van a enfadar y van a regatear el precio ✂️. Han previsto que van a bajar un 1% del precio original por cada 100 horas extras que se hagan de más.

Cuando Stephen, el jefe del departamento, ejecute el programa debería ver las 3 ofertas que son más rentables para la empresa con el siguiente formato:


Date: 25 January 1995

 Company              |    Income   |  Expenses  |  Benefit   
 ---------------------|:-----------:|:----------:|:------------:
 Banquio              | 400.000,00£ | 8.533,20€  | 545.633,53€
 Piedra negra         | 250.000,00€ | 40.000,00€ | 210.000,00€
 Endoso sobrecostes   | 100.000,00$ | 35.367,00€ | 59.377,39€

