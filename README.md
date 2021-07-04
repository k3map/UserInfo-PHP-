# UserInfo-PHP-

<h3>Obten informacion de quien visita tu sitio web!</h3>

<h4>Modo de uso</h4>
<p>
  <ul>
    <li><code>UserInfo::getIP();</code> Obtiene la IP del visitante| retorna  un string</li>
    <li><code>UserInfo::isProxy;</code> Verifica si la IP es un proxy | retorna  un bolean</li>
    <li><code>UserInfo::getUag;</code> Obtiene el agente de usuario| retorna  un string</li>
    <li><code>UserInfo::getOs;</code> Obtiene el sistema Operativo | retorna  un string</li>
    <li><code>UserInfo::getBrowser;</code> Obtiene el navegador del visitante | retorna  un string</li>
    <li><code>UserInfo::getLang;</code> Obtiene el lenguaje del visitante | retorna  un string</li>
    <li><code>UserInfo::getReferer;</code> Obtiene desde donde te visita el usuario | retorna  un string</li>
    <li><code>UserInfo::getHeaders;</code> Obtiene todas las cabezeras del visitante | retorna  un string</li>
    <li><code>UserInfo::getAllBrowserInfo;</code> Obtiene la ip, agente de usuario, sistema operativo, navegador, 
      version del navegador, lenguaje y referer del visitante | retorna  un array</li>
  </ul>
</p>
