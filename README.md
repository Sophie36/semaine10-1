semaine10-1 :

Présentation de l'exercice :

Faire un formulaire c'est bien, mais encore faut-il savoir quoi demander à l'utilisateur. Dans notre cas, nous allons faire simple et classique : un formulaire d'inscription. Notre formulaire d'inscription aura besoin de quelques informations concernant l'utilisateur, cela nous permettra d'utiliser un peu tous les éléments HTML spécifiques aux formulaires que nous avons vus jusqu'à présent. Voici les informations à récupérer ainsi que les types d'éléments HTML :

Information à relever                Type d'élément à utiliser 

  Sexe                                  <input type="radio"> 
  Nom                                   <input type="text">
  Prénom                                <input type="text">
  Âge                                   <input type="text"> 
  Pseudo                                <input type="text">
  Mot de passe                          <input type="password">
  Mot de passe (confirmation)           <input type="password">
  Pays                                  <select></select>
  Si l'utilisateur souhaite             <input type="checkbox">
  recevoir des mails 
  
  Bien sûr, chacune de ces informations devra être traitée afin que l'on sache si le contenu est bon. Par exemple, si l'utilisateur a bien spécifié son sexe ou bien s'il n'a pas entré de chiffres dans son prénom, etc. Dans notre cas, nos vérifications de contenu ne seront pas très poussées pour la simple et bonne raison que nous n'avons pas encore étudié les « regex » à ce stade du cours, nous nous limiterons donc à la vérification de la longueur de la chaîne ou bien à la présence de certains caractères. Bref, rien d'incroyable, mais cela suffira amplement car le but de ce TP n'est pas vraiment de vous faire analyser le contenu mais plutôt de gérer les événements et le CSS de votre formulaire.
  
