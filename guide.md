1. import Canvas from "@react-three/fiber" to render our chair model on the page
2. create an HTMLContent fnction so that we can render JSX on our canvas, by importing Html from "react-three/drei"
3. create our model function to display our armchair model, and use useGLTF which is a custom hook created by @react-three/drei because gltf files require loaders
4. render our model in our HTML content and render the HTML content in our Canvas in between Suspense (something the browser needs) and set fallback to null