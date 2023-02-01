## Versão customizada do glTF 2.0 format + Bloom

Nesta versão comentei a linha 64 em gltf2_blender_gather_materials.py

>emissive_factor = [f / emission_strength for f in emissive_factor]

Essa linha limita o **emissiveFactor** do **.gltf** exportado para no máximo 1 impedindo a utilização do Bloom para iluminação.

Com a linha removida, agora podemos utilizar valores maiores que 1 para dar o efeito Boom na emissão da iluminação

# Instalação

Para substituir o plugin do **glTF 2.0 format**, siga estes passos simples:

Esta versão é compatível com o Blender 3.3.3. Não funcionará em outras versões do Blender.

1. Feche o Blender caso o mesmo seteja aberto.
2. Baixe o arquivo **io_scene_gltf2** clicando em **Releases** em seguida clicando em **io_scene_gltf2.zip**;
3. Localize o local onde o Blender foi instalado
4. Descompact o Zip baixado na pasta **C:\Users\seu usuario\AppData\Roaming\Blender Foundation\Blender\3.0\scripts\addons** ou globalmente em **C:\Program Files\Blender Foundation\Blender 3.3\3.3\scripts\addons** subistituindo todos os arquivos do **io_scene_gltf2**;

Agora instale o glTF-Blender-IO-MSFS na versão versão 1.3.1.xx no link abaixo<br>
https://github.com/git-exahost/glTF-Blender-IO-MSFS/

