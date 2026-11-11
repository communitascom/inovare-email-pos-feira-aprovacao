# Inovare · prévia do e-mail pós-feira

E-mail de agradecimento aos visitantes do Dia do ACBr (05/11/2026), publicado no GitHub Pages para aprovação.

- `dados.enc` guarda o e-mail inteiro, com as imagens embutidas, cifrado (AES-GCM 256, chave derivada do PIN por PBKDF2-SHA256, 310000 iterações). Sem o PIN o conteúdo é ilegível.
- `index.html` contém só a tela de acesso; o e-mail é decifrado no navegador.
- O PIN é o mesmo da prévia do site da Inovare.

Feito pela Communitas.
