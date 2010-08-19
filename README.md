<h1>CouchDB: The Definitive Guide</h1>

<p>This is the source for the “CouchDB: The Definitive Guide” website.

<h2>Organisation</h2>

<dl>

<dt><code>draft/</code></dt>

<dd><p>The draft of next edition.</dd>

<dt><code>editions/</code></dt>

<dd><p>Published editions of the book.</dd>

<dt><code>editions/1</code></dt>

<dd><p>Edition 1 of the book.</dd>

<dt><code>editions/1/en</code></dt>

<dd><p>The English version of edition 1 of the book.</dd>

</dl>

<h2>Contributions</h2>

<p>The book is made available under the <a href="http://creativecommons.org/licenses/by/3.0/">Creative Commons Attribution</a> license.

<p>We encourage you to fork our work and make your own improvements under the terms of the license. If you have any changes you want to send back our way, please make a regular pull request via Github. If the authors like your changes, we may integrate them into the official book and give you a credit in the next edition. If you just have an issue to report, please use the regular Github issue system.

<h2>Publication</h2>

<p>Every once in a while, O’Reilly will take the current `en` version and turn it into a printed book. When that’s done, we’ll create a new directory under `editions/` to hold a stable snapshot of that release.

<h2>Translations</h2>

<p>We’d like to encourage you to start translating the book into your native language (or language of choice, really). We’re continuously publishing our work and all translations, so our readers always get the most up to date information.

<p>If you like to see a translation in a particular language, please first check if one exists already. If not, follow the instructions below.

<h3> Starting a Translation</h3>

<p>Only ever start a translation from the `en/` directory under `editions/<number>`. Do not try to translate `draft/` as it is constantly changing. Do not try to translate from any other language as `en/` is most likely the most complete source.

<p>Here’s how you would make a german (de) translation.

    cd editions/1
    cp -r en de
    git add de
    git commit -m 'Start German translation' de


<h4>Styles</h4>

<p>If you need custom CSS rules for your tranlsations, please create a new file `style.css` in `editions/1/de/` and add another `<link rel="stylesheet" href="../style.css">` line to your HTML files.

<h3>Publishing a Translation</h3>

<p>You’re free to publish a translation under the aforementioned license. O’Reilly voiced interest in publishing translations as well, but no definite plans have been made. We’re happy to put you in touch with our editor to discuss printed editions of translations further.

<h2>Relax</h2>