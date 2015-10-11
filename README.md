# TiTTun uudet sivut

[Jekyll](https://jekyllrb.com/) + [Bootstrap](http://getbootstrap.com/) + [GitHub](https://github.com/) = responsiivinen single page sivu, jonka päivitys ja ylläpito toimii täysin tätä repositorya muokkaamalla. 

**Muokkaaminen**
===

1. Varmista, että sinulla on oikeudet tittury-organisaatioon
2. Kloonaa repo lokaaliin ympäristöön 
> git clone https://github.com/tittury/tittury.github.io.git
3. Tee muokkaukset ja lisäykset
4. Lisää muokatut kamat committiin 
> git add .
5. Tee commit 
> git commit -m "Paras kommit ikinä"
6. Push! 
> git push origin master
7. ???
8. profit!

**Rakenne**
===
Uudet "sivut" luodaan _features -kansioon. Sivuissa käytetään [Markdown](https://daringfireball.net/projects/markdown/) -syntaksia. Sivutiedostoissa kannattaa käyttää 01-99 numerointia, jolla Jekyll järjestää valikon ja listauksen automaattisesti. Jokaisen tiedoston alkuun tulee lisätä kuvauskentät. Kuvaukseen voi lisätä kuvan osoitteen, jolloin kuva lisätään images-kansioon. 

>id: tittu  
>name: TiTTu ry?  
>heading: TiTTu ry  
>subheading:  Tampereen TietoTeekkarien tuki ry  
>image: './images/tittu_logo.png'  


**Lokaali devaus**
===
Jekyll on ihan pirun näppärä ja tukee hyvin lokaalia kehittämistä. Asenna koneelle [tarvittavat ohjelmat](http://jekyllrb.com/docs/installation/) ja Jekyll käynnistyy hyvinkin yksinkertaisesti:

> $ gem install jekyll
> $ cd gitfolder
> $ jekyll serve

Jolloin Jekyll starttailee lokaalisti http://localhost:4000 -osoitteeseen. Lisäksi se tarkkailee tiedostomuutoksia jatkuvasti, joten tiedoston muokkaus ja tallentaminen riittää sivujen uudelleen generoimiseen ja päivittämiseen. (Poislukien _config.yml)


**Vanhat hallitukset**
===
Vanhat hallitukset löytyvat _vanhat_hallitukset hakemistosta. Kopio joku
uudempi vuosi pohjaksi, esim vuodelle 2013:

> $ cd _vanhat_hallitukset/
> $ cp 2015.md 2013.md

Tämän jälkeen tee muutokset 2013.md:hen. Vanhat hallitukset listataan sivuille
reversed järjestyksessä joten pidetään tiedostonimet vain vuosien mukaan.
