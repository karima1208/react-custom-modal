# react-custom-modal-karima

> Une modal React simple, réutilisable et facile à intégrer dans vos projets React ✨  
> 📦 Publiée avec [create-react-library](https://github.com/transitive-bullshit/create-react-library)

[![NPM](https://img.shields.io/npm/v/react-custom-modal-karima.svg)](https://www.npmjs.com/package/react-custom-modal-karima)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

---

## 🚀 Installation

```bash
npm install --save react-custom-modal-karima
```

---

## 🧠 Utilisation

```tsx
import React, { useState } from 'react'
import Modal from 'react-custom-modal-karima'
import 'react-custom-modal-karima/dist/index.css'

function App() {
  const [isOpen, setIsOpen] = useState(false)

  return (
    <>
      <button onClick={() => setIsOpen(true)}>Ouvrir la modal</button>
      <Modal openModal={isOpen} setOpenModal={setIsOpen}>
        <p>Contenu de ma modal ✨</p>
      </Modal>
    </>
  )
}
```

---

## 🔧 Props disponibles

| Prop           | Type        | Description                                  |
| -------------- | ----------- | -------------------------------------------- |
| `openModal`    | `boolean`   | Contrôle l’ouverture de la modal             |
| `setOpenModal` | `function`  | Fonction pour fermer la modal (state setter) |
| `children`     | `ReactNode` | Le contenu à afficher dans la modal          |

---

## 📝 Licence

MIT © [karima1208](https://github.com/karima1208)

---

## 💌 Remerciements

Ce composant a été initialement conçu dans le cadre de ma formation [OpenClassrooms](https://openclassrooms.com).  
Merci à tous ceux qui m’ont aidée à apprendre et progresser ✨
