# Sobre o projeto

Através desse projeto pude desenvolver uma SPA (Single Page Application), com o framework React Router DOM, utilizando rotas aninhadas, rotas dinâmicas, fazendo uso dos hooks useLocation e useParams. Além disso desenvolvi todo o projeto de forma que os componentes fossem o máximo possível reaproveitáveis, assim reaproveitando alguns componentes em outras páginas para "economizar" linhas de código e tempo.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

{/*
  {/* Rotas aninhadas */}
  <Route path="/" element={<PaginaPadrao/>}>
    <Route path="/" element={<Inicio/>}/>
    <Route path="/sobremim" element={<SobreMim/>}/>
  </Route>

  --- Na rota "/", a estrutura a ser renderizada é:
  
    <PaginaPadrão>
      <Inicio/>
    </PaginaPadrão
  --- Na rota "/sobremim", a estrutura a ser renderizada é:
  
    <PaginaPadrao>
      <SobreMim/>
    </PaginaPadrao>
*/}
