
# Ignite Lab Design System

Ignite Lab is a short course provided by Rocketseat that teaches advanced topics in web development. This course took four days to watch and code along with teacher Diego Fernandes.

![storybook screenshot](https://github.com/LucasJantschChitolina/ignite-lab-design-system/blob/main/src/assets/storybook-print-screen.jpeg?raw=true)


Below you can check important information about what the project is:

## Cool stuff

 - Check the [Project Deployment](https://lucasjantschchitolina.github.io/ignite-lab-design-system)
 - Explore the [Figma Project](https://www.figma.com/file/bPnHBon9e5sFj0MQVsyA1H/Ignite-Lab?node-id=0%3A1)
 

## Learning

- Learned how to create a design system from scratch, from concepting the UI in figma to deploying in github actions
- New ways to use Figma better following the best practices
- Learned how to better use Figma as a developer
- Discovered a new way to create better components: the Composition Model
- First contact with TailwindCSS, a CSS framework that allows developers to build UIs faster and with more productivity 
- Managed my time to optimized learning

## Next steps

- Create new components and new pages to improve the project and test new things

## How to install

Install ignite-lab-design-system

```bash
  npm install 
  npm run storybook
```

## Use/Examples

Example on how to use the custom components created in this project.

```ts
import { TextInput } from "../components/TextInput";

function App() {
  return (
      <div>
        <TextInput.Root>
            <TextInput.Icon>
              <Envelope />
            </TextInput.Icon>

            <TextInput.Input type='email' placeholder='Type your e-mail'/>
        </TextInput.Root>
      </div>
  )
}
```

## Stack

**Front-end:** React, Vite, TailwindCSS

**Design:** Figma



