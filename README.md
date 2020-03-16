# Introducción
Esta página es  repositorio de los códigos utilizados para automatizar la generación de certificados de compras por parte de los clientes de Mercadro™.

# Estructura

## [docs](docs/index.html)
Representa los archivos utilizados en producción, evita editarlo directamente sin autorización.

## [checkoutStructure.json](checkoutStructure.json)
Representa la estructura capturada para un cliente test en la plataforma de Shopify, creada con fines de desarrollo de futuras aplicaciones y debugging sin necesidad de alteración del código en producción.

## [generarCertificado.liquid](generarCertificado.liquid)
Código utilizado en el checkout para enseñar un botón verde (ejemplo abajo) que lleva a la liga de generación de certificado al concluir la compra de un libro por parte de un cliente.

<style>
  button {
    margin-top: 25px;
    height: 3em;
    background-color: #28a745;
    color: white;
    width: 12em;
    font-size: 2em;
  }
  
  button:hover {
    background-color: #23963e;

    cursor: pointer;
  }
</style>
<button id="certificate">Generar Certificado</button>
