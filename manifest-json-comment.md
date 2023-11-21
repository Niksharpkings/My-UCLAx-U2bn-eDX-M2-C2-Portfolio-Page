{

* `name`: The name of the web application.
* `short_name`: A short name for the web application (max 12 characters).
* `start_url`: The URL of the page that the web application should start on.
* `icons`: An array of objects that specify the icons to be used for the web application. Each object contains the `src` URL of the icon, the `sizes` of the icon, and the `type` of the icon.
* `theme_color`: The primary color of the web application, used in the browser UI.
* `background_color`: The background color of the web application.
* `display`: Specifies how the web application should be displayed. In this example, we've set it to `standalone`, which means it should look and feel like a standalone native app. Other options include `fullscreen`, `minimal-ui`, and `browser`
* 

1. `scope`: Defines the URL scope of the web application. The scope determines which pages the service worker will control. For example, `"/my-app/"` would mean that the service worker only controls pages under the `/my-app/` directory.
2. `orientation`: Specifies the default orientation for the web application. The value can be one of `"any"`, `"natural"`, `"landscape"`, or `"portrait"`.
3. `lang`: Defines the default language for the web application. This should be a valid language tag, such as `"en-US"` or `"fr-CA"`.
4. `dir`: Specifies the default text direction for the web application. The value can be `"ltr"` for left-to-right or `"rtl"` for right-to-left languages.
5. `description`: A short description of the web application, typically used by search engines and app stores.
6. `short_name`: A short name for the web application (max 12 characters) that will be displayed on the user's home screen or app launcher.
7. `related_applications`: An array of objects that specify related native apps for the web application. Each object contains properties such as `platform`, `url`, and `id`.
8. `prefer_related_applications`: A boolean value that indicates whether the user should be prompted to install a related native app instead of using the web application.
9. `shortcuts`: An array of objects that define shortcuts to specific pages or actions within the web application. Each object contains properties such as `name`, `description`, and `url`.

"name":"Ńἱĸἱ৳α Shârρἱo's aka Niksharpkings UCLAx+U2 Profile Resume github page",

  "short_name":"Niksharpkings UCLAx+U2 Profile",

  "id":"/index.html",

  "start_url":"/index.html",

  "background_color":"#2774ae",

  "display":"browser",

  "scope":"/",

  "theme_color":"#2774ae",

  "orientation":"portrait-primary",

  "lang":"en-US",

  "dir":"ltr",

  "description":"Ńἱĸἱ৳α Shârρἱo's aka Niksharpkings UCLAx+U2 Profile Resume github page",

  "icons":[

    {

    "src":"./assets/manifestIcon/maskable_icon.png",

    "type":"image/png",

    "sizes":"250×250"

    },

    {

    "src":"./assets/manifestIcon/maskable_icon_x192.png",

    "type":"image/png",

    "sizes":"192x192"

    },

    {

    "src":"./assets/manifestIcon/maskable_icon_x128.png",

    "type":"image/png",

    "sizes":"128x128"

    },

    {

    "src":"./assets/manifestIcon/maskable_icon_x96.png",

    "type":"image/png",

    "sizes":"96x96"

    },

    {

    "src":"./assets/manifestIcon/maskable_icon_x72.png",

    "type":"image/png",

    "sizes":"72x72"

    },

    {

    "src":"./assets/manifestIcon/maskable_icon_x48.png",

    "type":"image/png",

    "sizes":"48x48"

    }

  ],

  "shortcuts":[

    {

    "name":"Avatar",

    "short_name":"nikavatar",

    "description":"myavatar",

    "url":"/assets/images/avatarNikShar2022.webp",

    "icons":[{"src":"/assets/manifestIcon/maskable_icon_x192.png","sizes":"192x192"}]

    },

    {

    "name":"Avatar2",

    "short_name":"nikavatar2",

    "description":"myavatar2",

    "url":"/assets/images/avatarNikShar2022.webp",

    "icons":[{"src":"/assets/manifestIcon/maskable_icon_x192.png","sizes":"128x128"}]

    }

  ],

  "screenshots":[

    {

    "src":"/image/README/1676130578243.png",

    "type":"image/png",

    "sizes":"2812x7156",

    "form_factor":"narrow"

    }

  ]

}
