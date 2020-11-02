# Máscaras-para-input
#
# RUN
## Crie um arquivo ex(mascara.js)
> - Import esse arquivo para dentro da página que contém seu form ou para uma pasta que import globalmente</p>
> - Nomeie os campos do input de acordo os nomes que estão dentro do campo do arquivo(mascara.js)

- #### ex: <.input type="text" id="cpf">

# CÓDIGO DA MÁSCARA

```
$(document).ready(function(){
      $('#telefone').mask('(00) 00000-0000');
      $('#cpf').mask('000.000.000-00');
      $('#cep').mask('00000-000');

      }); 
