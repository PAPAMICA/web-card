# web-card
Une vcard web partageable et ajoutable en un clic au répertoire !

![demo](demo.gif)

## Personnalisation

### /json_data.js
```js
json_data = {
    show_directions: false,
    showPreview: 1,
    form: [{ section_design: { fold: false } }, { section_information: { fold: false } }, { section_social: { fold: true } }, { section_welcome_screen: [] }, { section_advance_options: { fold: false } }],
    url: "<website>",
    color1: "#0288d1",
    color2: "#64b5f6",
    avatar: "img/logo.png",
    avatar_extra: { zoom: 100, background: "#ffffff" },
    address: { autocomplete: "disabled" },
    welcome_screen: "img/logo.png",
    welcome_extra: { zoom: 50, background: "#ffffff" },
    sharing: true,
    code: {
        channels: [
            { input_prefix_label: "URL", link: "<url>", label: "", name: "Facebook" },
            { input_prefix_label: "@", link: "<username>", label: "", name: "Twitter" },
            // { input_prefix_label: "@", link: "<username>", label: "", name: "Instagram" },
            // { input_prefix_label: "URL", link: "<url>", label: "Find us on TikTok", name: "TikTok" },
            // { input_prefix_label: "Phone", link: "<numbers_phone>", label: "Message us", name: "WhatsApp" },
            // { input_prefix_label: "URL", link: "<url>", label: "Find us on TikTok", name: "TikTok" },
            // { input_prefix_label: "URL", link: "<url>", label: "", name: "YouTube" },
            // { input_prefix_label: "URL", link: "<url>", label: "Get in touch", name: "Telegram" },
            // { input_prefix_label: "URL", link: "<url>", label: "Get in touch", name: "Messenger" },
            // { input_prefix_label: "URL", link: "<url>", label: "Review us on Google", name: "Google Review" },
            // { input_prefix_label: "URL", link: "<url>", label: "", name: "Tripadvisor" },
            // { input_prefix_label: "URL", link: "<url>", label: "", name: "LinkedIn" },
            // { input_prefix_label: "URL", link: "<url>", label: "Order with Uber Eats", name: "Uber Eats" },
            // { input_prefix_label: "URL", link: "<url>", label: "", name: "Dribbble" },
            // { input_prefix_label: "URL", link: "<url>", label: "", name: "VKontakte" },
            // { input_prefix_label: "URL", link: "<url>", label: "Listen to us on Spotify", name: "Spotify" },
            // { input_prefix_label: "URL", link: "<url>", label: "Make a reservation", name: "OpenTable" },
            // { input_prefix_label: "URL", link: "<url>", label: "", name: "Pinterest" },
        ],
    },
    firstname: "<firstname>",
    lastname: "<lastname>",
    numbers_mobile: "<numbers_mobile>",
    numbers_phone: "<numbers_phone>",
    numbers_fax: "<numbers_fax>",
    email: "<email>",
    company: "<company>",
    job: "<job>",
    venue: "<venue>",
    street: "<street>",
    street_number: "<street_number>",
    state: "<state>",
    city: "<city>",
    zip: "<zip>",
    country: "<country>",
    website: "<website>",
    bio: "<bio>",
};
```

Remplacez les valeurs suivantes :
- website
- url
- username

Ainsi que les variables pour votre adresse et contact.
Vous pouvez décommentez les réseaux sociaux que vous souhaitez. 

### /img/logo.png
Vous pouvez mettre votre logo dans `/img/logo.png`.

### /img/favicon/favicon.ico
Vous pouvez mettre votre logo pour le favicon ici `/img/favicon/favicon.ico`.

### /vcard.vcf
C'est ici que vous mettez votre vcard. Je vous laisse un modèle à remplir au cas ou.
```
BEGIN:VCARD
VERSION:3.0
PRODID:
N:
FN:
ORG:
TITLE:
EMAIL;TYPE=PREF,INTERNET:
TEL;TYPE=CELL,voice:
TEL;TYPE=WORK,voice:
TEL;TYPE=WORK,fax:
ADR;TYPE=
URL:

PHOTO;TYPE=JPG;ENCODING=

NOTE:

REV:2008-04-24T19:52:43Z
END:VCARD
```
