# Gestionnaire d'agenda
<br>
<a href=""><img src="http://www.thebluediamondgallery.com/wooden-tile/images/agenda.jpg"alt="Agenda, image de TheBlueDiamondGallery.com"></a><br>
<br>
<br>


<p align='center'>
  <a href="https://github.com/isabelleysseric/Agenda">Agenda</a> (GitHub)
  &nbsp; • &nbsp;<a href="https://github.com/isabelleysseric/Agenda/wiki">Agenda</a> (Wiki)<br/>
  <a href="https://github.com/isabelleysseric">isabelleysseric</a> (GitHub)
  &nbsp; • &nbsp;<a href="https://isabelleysseric.com/">isabelleysseric.com</a> (Portfolio)
  &nbsp; • &nbsp;<a href="https://www.linkedin.com/in/isabelle-eysseric/">isabelle-eysseric</a> (LinkedIn) <br/>
</p>
<br/>
<br/>


## AUTEUR:<br>
============
<p> Isabelle EYSSERIC</p>
<br>
<br>


## ETAT DU PROJET:<br>
==================
<p>Version initiale</p>
<br>
<br>


## DESCRIPTION:<br>
================
<p> L'agenda est représenté dans le programme par un dictionnaire avec trois clés: <code>proprio</code>, <code>evenements</code> et <code>max_id</code>. </p>
<br>
<p>La valeur liée à <code>proprio</code> est le nom du propriétaire de l’agenda. </p>
<p>La valeur liée à <code>max id</code> est un entier qui permet de garder le compte de l’identifiant le plus grand des événements.</p>
<p>La valeur liée à <code>evenements</code> est une liste contenant des événements, où chaque événement est aussi un dictionnaire avec les champs : </p>
<li><code>id</code> (l’identifiant de l’événement), </li>
<li><code>date</code> (la date de l’événement), </li>
<li><code>heure_debut</code> (l’heure à laquelle l’événement débute), </li>
<li><code>heure_fin</code> (l’heure à laquelle l’événement se termine), </li>
<li><code>titre</code> (le titre ou le nom de l’événement) et </li>
<li><code>lieu</code> (le lieu où se déroule l’événement). </li>
<br>
<br>


## UTILISATION:<br>
===============
<p>Le  programme contient un seul fichier <code>agenda.py</code> avec les méthodes:</p>
<li> <code>str_to_date</code></li>
<li> <code>str_to_heure</code></li>
<li> <code>creer_agenda</code></li>
<li> <code>creer_evenement</code></li>
<li> <code>evenement_to_str</code></li>
<li> <code>sauvegarder_agenda</code></li>
<li> <code>charger_agenda</code></li>
<li> <code>saisir_evenement</code></li>
<li> <code>evenements_en_conflit</code></li>
<li> <code>ajouter_evenement</code></li>
<li> <code>supprimer evenement</code></li>
<li> <code>afficher_menu</code></li>
<li> <code>main</code></li>
  <br>
<p>Pour démarrer, choisir une option dans le menu. Les options sont: </p>
<li> <code>1- Créer un nouvel agenda</code></li>
<li> <code>2- Ouvrir un agenda existant</code></li>
<li> <code>3- Sauvegarder les modifications effectuées</code></li>
<li> <code>4- Ajouter un évènement</code></li>
<li> <code>5- Supprimer un évènement</code></li>
<li> <code>6- Afficher l'agenda</code></li>
<li> <code>7- Quitter</code></li><br>
<br>
<br>
