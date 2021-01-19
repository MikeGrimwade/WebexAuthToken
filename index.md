<HTML>

<HEAD>

<TITLE>Your Title Here</TITLE>
<script>

</script>
</HEAD>

<BODY BGCOLOR="FFFFFF">

<CENTER><IMG SRC="clouds.jpg" ALIGN="BOTTOM"> </CENTER>

<HR>

<a href="http://somegreatsite.com">Link Name</a>

is a link to another nifty site

<H1>This is a Header</H1>

<H2>This is a Medium Header</H2>

Send me mail at <a href="mailto:support@yourcompany.com">

support@yourcompany.com</a>.

<P> This is a new paragraph!
<script>

function getParameterByName(name, url = window.location.href) {
    name = name.replace(/[\[\]]/g, '\\$&');
    var regex = new RegExp('[?&]' + name + '(=([^&#]*)|&|#|$)'),
        results = regex.exec(url);
    if (!results) return null;
    if (!results[2]) return '';
    return decodeURIComponent(results[2].replace(/\+/g, ' '));
}

var foo = getParameterByName('foo'); // "lorem"
var bar = getParameterByName('bar'); // "" (present with empty value)
var baz = getParameterByName('baz'); // "" (present with no value)
var qux = getParameterByName('qux'); // null (absent)

document.write(foo + "<br>");
document.write("Did it");

</script>
<BR> <B><I>This is a new sentence without a paragraph break, in bold italics.</I></B>

<HR>

</BODY>

</HTML>
