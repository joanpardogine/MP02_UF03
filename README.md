# Documentació (pdf)

## 1. [Gestió usuaris](documents/Apunts_MP02_UF03_Llenguatges_DCL_01_Gestio_Usuaris.pdf)

## 2. [Procediments, funcions i Cursors ](documents/Apunts_MP02_UF03_Llenguatges_DCL_02_Proc_Func_Cursors.pdf)


[CreaDBLlibreria.sql](https://drive.google.com/open?id=1O2YgMggEx0dswZZncbXx-ozH2nLDzcUk)

## Comandes per actualitzar a mySQL 8.0

sudo apt-get update

sudo apt-get upgrade

wget https://repo.mysql.com//mysql-apt-config_0.8.14-1_all.deb

sudo dpkg -i mysql-apt-config_0.8.14-1_all.deb


# Activitat 1: Usuaris i privilegis en MySQL.

<details>
  <summary> fes click per expandir.</summary>

&nbsp;&nbsp;**1.** Crea un usuari nou amb el teu **`cognomnom`** en el servidor local.

&nbsp;&nbsp;**2.** Proporciona els permisos per la BD **`videoclub`** al nou usuari:

&nbsp;&nbsp;&nbsp;&nbsp;**a.** Llistar dades.

&nbsp;&nbsp;&nbsp;&nbsp;**b.** Inserir dades.

&nbsp;&nbsp;&nbsp;&nbsp;**c.** Modificar dades.

&nbsp;&nbsp;&nbsp;&nbsp;**d.** Esborrar dades.

&nbsp;&nbsp;&nbsp;&nbsp;**e.** Executar funcions.

&nbsp;&nbsp;**3.** Aplica els privilegis.

&nbsp;&nbsp;**4.** Mostra els privilegis del nou usuari.

&nbsp;&nbsp;**5.** Crea un usuari nou amb el teu **`cognomnom_admin`**.

&nbsp;&nbsp;**6.** Proporciona tots els privilegis per la BD **`videoclub`** a l’usuari creat en l'**`apartart 5`**

&nbsp;&nbsp;**7.** Esborra el privilegi de crear taules a l’usuari creat en l'**`apartart 5`**.

&nbsp;&nbsp;**8.** Aplica els privilegis.

&nbsp;&nbsp;**9.** Mostra els privilegis de l’usuari creat en l'**`apartart 5`**.

&nbsp;&nbsp;**10.** Surt del MySQL i accedeix amb l’usuari creat en l'**`apartart 1`**.

&nbsp;&nbsp;**11.** Llista totes les pel·lícules.

&nbsp;&nbsp;&nbsp;&nbsp;**a.** Pots fer-ho?

&nbsp;&nbsp;&nbsp;&nbsp;**b.** En cas negatiu, per què?

&nbsp;&nbsp;**12.** Llistat tots els empleats de la BD **`empresa`**.

&nbsp;&nbsp;&nbsp;&nbsp;**a.** Pots fer-ho?

&nbsp;&nbsp;&nbsp;&nbsp;**b.** En cas negatiu, per què?

&nbsp;&nbsp;**13.** Esborra l’usuari creat en l'**`apartart 5`**.


&nbsp;&nbsp;Creeu un fitxer sql amb el resultat de cada apartat. Per exemple, el nom del fitxer que
conté la solució a l'**`apartart 1`** serà:

&nbsp;&nbsp;**`CognomNom_Act_01_UsuPri_MySQL_Apartat_001.sql`**
&nbsp;&nbsp;I el lliurament, serà un fitxer comprimit (**`zip`**, o **`rar`**) que contindrà tots els fitxers sql de cadascun dels apartats.

&nbsp;&nbsp;**`CognomNom_Act_01_UsuPri_MySQL.zip`**

&nbsp;&nbsp;Recordeu que la correcció la faré pujant el fitxer que m'enviïs i executant-lo directament
al meu servidor. Per tant, sabreu si em funcionarà o no, si executant-lo vosaltres en el
vostre servidor funciona o no.

</details>

# Activitat 2: Treballadors amb fills.
<details>
  <summary> fes click per expandir.</summary>
</details>
  

# Activitat 3: Activitats de procediments emmagatzemats

<details>
  <summary> fes click per veure l'enllaç a: Activitat 3: Activitats de procediments emmagatzemats. (PDF)</summary>

## 1. [Activitat_03_Procediments_Funcions_MySQL](documents/Activitat_03_Procediments_Funcions_MySQL.pdf)

</details>


# Enunciats per practicar amb els `INSERT`'s

<details>
  <summary> fes click per expandir.</summary>

![MER_Videoclub](./imatges/MER_Videoclub.png)


**1.** Emprant la base de dades **`videoclub`**, cal que:
Insertis, com a mínim **tres** registres, a **totes** i cadascuna de les **taules** que existeixen a la base de dades de **`videoclub`**.


~~~~sql
+---------------------+
| Taules a videoclub  |
+---------------------+
| ACTORS              |
| ACTORS_PELLICULES   |
| DIRECTORS           |
| EXEMPLARS           |
| PELLICULES          |
| PRESTECS            |
| SOCIS               |
+---------------------+
~~~~
La informació de cada pel·lícula cal que la obtingeu de la web [IMDb.com](https://www.imdb.com/). ![logoIMDb](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/IMDB_Logo_2016.svg/245px-IMDB_Logo_2016.svg.png)
</details>
