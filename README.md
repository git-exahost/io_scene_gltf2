## Versão customizada do glTF 2.0 format + Bloom

Nesta versão comentei a linha 64 em gltf2_blender_gather_materials.py

>emissive_factor = [f / emission_strength for f in emissive_factor]

Essa linha limita o **emissiveFactor** do **.gltf** exportado para no máximo 1 impedindo a utilização do Bloom para iluminação.

Com a linha removida, agora podemos utilizar valores maiores que 1 para dar o efeito Boom na emissão da iluminação

# Instalação

Para subistituir o plugin do **glTF 2.0 format**, siga estes passos simples:

Esta versão é compatível com o Blender 3.3.x e inferior. Não funcionará com o Blender 3.4 ou superior.

1. Feche o Blender caso o mesmo seteja aberto.
2. Baixe o arquivo **io_scene_gltf2** clicando no icone **<> Code** em seguida clicando em **Download ZIP**
3. Localize o local onde o Blender foi instalado
4. Subistitua todos os arquivos da pasta **io_scene_gltf2** em "Blender Foundation\Blender 3.3\3.3\scripts\addons\io_scene_gltf2" pelos arquivos do zip baixado

Para funcionar instale o **glTF-Blender-IO-MSFS** na versão versão **1.3.1** no link abaixo<br>
https://github.com/git-exahost/glTF-Blender-IO-MSFS/blob/main/README.md

