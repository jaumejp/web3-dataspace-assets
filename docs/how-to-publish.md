# Cómo publicar datasets en Ocean Protocol

1. Subir el fichero al repositorio.
2. Crea un archivo `metadata.json` como los ejemplos en `datasets/`.
3. Opcional: adapta una plantilla como `metadata-templates/ocean-template.json`.
4. Usa [Ocean Market](https://market.oceanprotocol.com/) o despliega tu propio proveedor.
5. Sigue los pasos para crear un asset:
   - Conecta tu wallet (Metamask)
   - Elige "Data NFT + Datatoken"
   - Rellena el formulario usando los valores de `metadata.json`
6. Publica el asset.

Los datos deben estar accesibles públicamente por URL, por ejemplo vía GitHub raw:
