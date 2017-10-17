# seo
backlink

Merhabalar;

Genelde lazım olmaz ama lazım olur diye paylaşalım istedik, WordPress sitenizde ve ya temasında dış bağlantıları kullanıcılara belirtmek için ona özel bir stil uygulayabilirsiniz. Aşağıdaki kodlar ile dış ve iç linkleri bir birinden farklı bir stile çevirebilirsiniz.

WordPress için

<pre>
<style>
a[href*=”//”]:not([href*=”<?php echo filter_input(INPUT_SERVER, ‘SERVER_NAME’); ?>”])
{
/* dış linklere uygulanacak kod */
}
<style>
</pre>


yukarıdaki kodu wordpress için uygulayabilirsiniz.
<br />
https://www.kibirlikirpi.com/wordpress-dis-baglantilara-stil-ekleme/
