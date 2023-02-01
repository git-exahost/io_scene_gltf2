## Versão customizada do glTF 2.0 format + Bloom

Nesta versão foi comentada a linha 64 do arquivo **gltf2_blender_gather_materials.py** em **blender\exp\gltf2_blender_gather_materials.py**

>emissive_factor = [f / emission_strength for f in emissive_factor]

Essa linha limita o **emissiveFactor** do **.gltf** exportado para no máximo 1 impedindo a utilização do Bloom para iluminação.

Com a linha removida, agora podemos utilizar valores maiores que 1 para dar o efeito Boom na emissão da iluminação

Esta versão é compatível com o **Blender 3.3.3**. Até o momento esta versão não funciona em outros versões do Blender, então instale o Blender 3.3.3 utilizando o link abaixo:<br>
https://www.blender.org/download/releases/3-3/

## Instalação

Para substituir o plugin do **glTF 2.0 format**, siga estes passos simples:

Esta versão é compatível com o Blender 3.3.3. Não funciona em outras versões do Blender.

1. Feche o Blender;
2. Baixe o arquivo **io_scene_gltf2** clicando em **Releases** em seguida clicando em **io_scene_gltf2.zip**;
3. Localize a pasta onde o Blender foi instalado;
4. Descompact o Zip baixado na pasta **C:\Users\seu usuario\AppData\Roaming\Blender Foundation\Blender\3.0\scripts\addons** ou globalmente em **C:\Program Files\Blender Foundation\Blender 3.3\3.3\scripts\addons** substituindo todos os arquivos da pasta **io_scene_gltf2** pelos arquivos do zip baixado;

Agora instale o **glTF-Blender-IO-MSFS** na versão versão 1.3.1.x no link abaixo:<br>
https://github.com/git-exahost/glTF-Blender-IO-MSFS/

