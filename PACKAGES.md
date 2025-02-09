# Configurações necessárias

viteconfig: 

export default defineConfig({
  plugins: [react()],
   optimizeDeps: {
    include: ['three']
  }  
})


# Pacotes instalados

**Biome JS**

Instalação:

npm install --save-dev --save-exact @biomejs/biome

Configuração:

npx @biomejs/biome init

**Three JS**

Instalacao:

npm install three

npm install @types/three

**Outros**

npm install stats-gl
npm install three-subdivide
npm install three-mesh-bvh
npm i web-ifc
npm install three-bvh-csg
npm install three-gpu-pathtracer
npm install flow
