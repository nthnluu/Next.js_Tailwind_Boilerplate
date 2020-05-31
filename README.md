# Next.JS + Tailwind Boilerplate


## About <a name = "about"></a>
This is a barebones Next.JS project configured to work with Tailwind CSS, a utility-first CSS framework. 

## Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Clone the repo

To get started, simply clone the repository.

```
git clone https://github.com/nthnluu/next-tailwind-boilerplate.git
```

### Installing

Once you clone the repository, navigate into the project directory and npm `npm install` in order to install  the project dependencies.


```
cd next-tailwind-boilerplate
```

```
npm install
```

That is all there is to it! You can now run the development server and see the website in action.
```
npm run dev
```

## Customizing Tailwind <a name = "usage"></a>

This project comes with a `tailwind.config.js` file in the `root` directory. Here,  you can apply any customizations you would like. See the Tailwind CSS documentation for more information.

You can also take advantage of the `@apply` CSS directive, which allows you to combine Tailwind classes into a single class. This is very useful for updating reused CSS and keeping your component syntax clean.
