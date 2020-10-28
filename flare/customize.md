# Customizing Flare

## Design

Flare is designed to be customizable to fit your VA's Brand. This can be done on your site under **Site Settings** in the **Site Design** tab, 
which can be found by staff members with access under the Admin Menu.

Here, you can set various options. These include your main color, text color, and any custom CSS you'd like to add to your site. CSS is a language used to make websites looks nice. For example, here's how you can use a font from [Google Fonts](https://fonts.google.com/).

```css
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');

* {
    font-family: 'Bebas Neue', cursive;
}
```

## Content

Some basic content aspects of Flare can be customized using the **VA Settings** tab of **Site Settings**. These include your VA Name (shown in the navbar), VA Logo (overrides your VA Name in the navbar if set), and your callsign format set using [RegEx](https://en.wikipedia.org/wiki/Regular_expression). RegEx is a language for matching complex strings, where certain parts need to be the same, but others may differ. 

Flare includes 2 pre-fill options to help you out. For the `Airline 123VA` format, click the relevant link, enter your airline callsign (American, Speedbird, etc) then hit enter. Everything else is done for you.