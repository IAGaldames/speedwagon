---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
image: speedwagoncover.jpg
---

{% include hero.html
id="catalogo"
container_class="container-fluid bg-dark text-light"
img_col="6"
order_img="order-0"
text_col="6"
link="/catalogo"
title="Catálogo de libros"
btn_class="btn-light"
btn_text="Comprar Aquí"
%}

{% include hero.html
id="sellos"
container_class="container bg-warning rounded"
img_col="9"
order_img="order-1"
text_col="3"
link="/sellos"
title="Nuestros Sellos"
btn_class="btn-dark"
btn_text="Conócelos"
%}

{% include hero.html
id="autores"
container_class="container-fluid bg-light
text-dark"
img_col="6"
order_img="order-0"
text_col="6"
link="/autores"
title="Nuestros autores"
btn_class="btn-dark"
btn_text="Conócelos"
%}

{% include hero.html
id="noticias"
container_class="container bg-light
rounded"
img_col="6"
order_img="order-1"
text_col="6"
link="/noticias"
title="Noticias"
btn_class="btn-danger"
btn_text="Infórmate"
%}

{% include hero.html
id="instagram"
container_class="container-fluid bg-danger-subtle"
img_col="4"
order_img="order-0"
text_col="8"
link="https://www.instagram.com/speedwagon_media_works/"
title="Síguenos en Instagram"
btn_class="btn-danger"
btn_text="speedwagon_media_works"
%}


{% include hero.html
id="manuscritos"
container_class="container bg-success-subtle"
img_col="6"
order_img="order-1"
text_col="6"
link="/manuscritos"
title="Recepción de manuscritos"
btn_class="btn-danger"
btn_text="Saber más"
%}