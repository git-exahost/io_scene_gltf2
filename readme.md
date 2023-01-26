* Versão customizada do glTF 2.0 format

Nesta versão comentei a linha 64 em gltf2_blender_gather_materials.py

emissive_factor = [f / emission_strength for f in emissive_factor]

Essa linha limita o emissiveFactor do .gltf exportado para no máximo 1 impedindo a utilização do Bloom para iluminação.

Com a linha removida, agora podemos utilizar valores maiores que 1 para dar o efeito Boom na emissão da iluminação