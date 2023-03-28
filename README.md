
![Github Finder Desktop](/img_readme/github_finder.png)

Tabela de conteúdos
=================
   * [Links](#Links)
   * [Desenvolvimento](#Desenvolvimento)
      * [Desenvolvido com](#Desenvolvido-com)
   * [O que Aprendi](#o-que-aprendi)
   * [Autor](#autor)

## Overview
Um SPA feito em React e Typescript, integrando uma API do Github onde o nome de usuário digitado retorna os dados do Perfil do Github dele.

## Links

Live site URL: [https://otavio-fina.github.io/react-github-perfil-finder/](https://otavio-fina.github.io/react-github-perfil-finder/dist)



## Desenvolvimento

### Deselvolvido com:

- ![HTML](/img_readme/Tech-Stack-Logos/html5.png)
- ![CSS](/img_readme/Tech-Stack-Logos/css.png)
- ![JAVASCRIPT](/img_readme/Tech-Stack-Logos/js.png)
- ![REACT](/img_readme/Tech-Stack-Logos/reactjs.png)
- ![GIT](/img_readme/Tech-Stack-Logos/git.png)
- ![GITHUB](/img_readme/Tech-Stack-Logos/gitlab.png)
- ![VITE](/img_readme/Tech-Stack-Logos/vitejs.png)


### O que eu aprendi

Foi usado o _*react router*_ no codigo, e isso desenvolveu minhas habilidades nele
```jsx
import { createBrowserRouter, RouterProvider } from 'react-router-dom'

const router = createBrowserRouter([
  {
    path: "/",
    element: <App />,
    children: [
      {
        path: "/",
        element: <Home />        
      }
    ]
  }
])

ReactDOM.createRoot(document.getElementById('root') as HTMLElement).render(
  <React.StrictMode>
    <RouterProvider router={router} />
  </React.StrictMode>,
)

```

Além disso, houve o uso do typescript, que também a me desenvolver nessa tecnologia. podemos ver um dos usos do código _ts_ no bloco a seguir:

```typescript
export type UserProps = {
    avatar_url: string,
    login: string,
    location: string,
    followers: number;
    following: number
}
```


 
## Autor
- Website - [otaviofina.website](otaviofina.website)
- E-mail - otaviofina@gmail.com
- Linkedin - [https://www.linkedin.com/in/otavio-fina](https://www.linkedin.com/in/otavio-henrique-samuel-dos-santos-fina-325108256/)
