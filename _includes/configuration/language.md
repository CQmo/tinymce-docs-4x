## language

This option allows you to specify the language that TinyMCE's user interface will appear in. That is, the toolbar buttons and menu items. By default, TinyMCE will use US English as the language of the interface.

If you wish to use a language other than English, please follow these steps:

1. Download the TinyMCE 4 language pack [from here](https://www.tiny.cloud/docs-4x/language/tinymce4x_languages.zip).
2. Unpack the language `.js` file into your `tinymce/langs` folder.
3. Set the [`language`]({{ site.baseurl }}/configure/localization/#language) option in your TinyMCE configuration to the language code in the list below the example.
4. Confirm that the language has been set successfully by loading TinyMCE.

Please note, the language code you set in your TinyMCE configuration must match the filename of the language file. If the language file is not found, TinyMCE will not load.

**Type:** `String`

**Default Value:** `en_US`

##### Example

In this example we will set the editor language to Swedish.

```js
tinymce.init({
  selector: 'textarea',  // change this value according to your HTML
  language: 'sv_SE'
});
```

The available language codes for use with this option are as follows:

| Language                      |  Code   |
| :-----------------------------| :-------|
| Arabic                        | ar      |
| Arabic (Saudi Arabia)         | ar_SA   |
| Armenian                      | hy      |
| Azerbaijani                   | az      |
| Basque                        | eu      |
| Belarusian                    | be      |
| Bengali (Bangladesh)          | bn_BD   |
| Bosnian                       | bs      |
| Bulgarian (Bulgaria)          | bg_BG   |
| Catalan                       | ca      |
| Chinese (China)               | zh_CN   |
| Chinese (Taiwan)              | zh_TW   |
| Croatian                      | hr      |
| Czech                         | cs      |
| Danish                        | da      |
| Divehi                        | dv      |
| Dutch                         | nl      |
| English (Canada)              | en_CA   |
| English (United Kingdom)      | en_GB   |
| Estonian                      | et      |
| Faroese                       | fo      |
| Finnish                       | fi      |
| French (France)               | fr_FR   |
| Gaelic, Scottish              | gd      |
| Galician                      | gl      |
| Georgian (Georgia)            | ka_GE   |
| German                        | de      |
| German (Austria)              | de_AT   |
| Greek                         | el      |
| Hebrew (Israel)               | he_IL   |
| Hindi (India)                 | hi_IN   |
| Hungarian (Hungary)           | hu_HU   |
| Icelandic (Iceland)           | is_IS   |
| Indonesian                    | id      |
| Italian                       | it      |
| Japanese                      | ja      |
| Kabyle                        | kab     |
| Kazakh                        | kk      |
| Khmer (Cambodia)              | km_KH   |
| Korean (Korea)                | ko_KR   |
| Kurdish                       | ku      |
| Kurdish (Iraq)                | ku_IQ   |
| Latvian                       | lv      |
| Lithuanian                    | lt      |
| Luxembourgish                 | lb      |
| Malayalam                     | ml      |
| Malayalam (India)             | ml_IN   |
| Mongolian (Mongolia)          | mn_MN   |
| Norwegian Bokmål (Norway)     | nb_NO   |
| Persian                       | fa      |
| Persian (Iran)                | fa_IR   |
| Polish                        | pl      |
| Portuguese (Brazil)           | pt_BR   |
| Portuguese (Portugal)         | pt_PT   |
| Romanian                      | ro      |
| Russian                       | ru      |
| Serbian                       | sr      |
| Sinhala (Sri Lanka)           | si_LK   |
| Slovak                        | sk      |
| Slovenian (Slovenia)          | sl_SI   |
| Spanish                       | es      |
| Spanish (Mexico)              | es_MX   |
| Swedish (Sweden)              | sv_SE   |
| Tajik                         | tg      |
| Tamil                         | ta      |
| Tamil (India)                 | ta_IN   |
| Tatar                         | tt      |
| Thai (Thailand)               | th_TH   |
| Turkish                       | tr      |
| Turkish (Turkey)              | tr_TR   |
| Uighur                        | ug      |
| Ukrainian                     | uk      |
| Ukrainian (Ukraine)           | uk_UA   |
| Vietnamese                    | vi      |
| Vietnamese (Viet Nam)         | vi_VN   |
| Welsh                         | cy      |
