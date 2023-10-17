# Hermes

## Project Setup

Copy the repository to your machine

```bash
$ git clone https://github.com/Sir-Aguiar/Hermes.git Hermes
```

Open the directory that've been created

```bash
$ cd Hermes
```

Install all dependencies

```bash
$ npm install
```

Run the development server

```bash
$ npm run dev
```

## Environment

Setup a `.env` file in the root of the project. This will only be visible on your machine. So you're free to place sensitive informations there. All of the environment variables are listed down here (Name -> Type -> Description):

Quando você quer enviar dados ao seu servidor, você quer eles protegidos, validados e no formato correto.
Então vamos começar por isso.
Quando se iniciar um input, informe o nome que ele receberá. Então será atribuído um espaço à este propriedade no objeto de estado.