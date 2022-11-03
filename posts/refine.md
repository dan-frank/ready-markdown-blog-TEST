<br/>

<div align="center" style="margin: 30px;">
<a href="https://refine.dev/">
  <img src="https://raw.githubusercontent.com/refinedev/refine/master/logo.png"   style="width:250px;" align="center" />
</a>
<br />
<br />

<div align="center">
    <a href="https://refine.dev">Home Page</a> |
    <a href="https://discord.gg/refine">Discord</a> |
    <a href="https://refine.dev/examples/">Examples</a> | 
    <a href="https://refine.dev/blog/">Blog</a> | 
    <a href="https://refine.dev/docs/">Documentation</a> | 
    <a href="https://github.com/refinedev/refine/projects/1">Roadmap</a>
</div>

</div>
<br/>

<div align="center"><strong>Build your <a href="https://reactjs.org/">React</a>-based CRUD applications, without constraints.</strong><br>An open source, headless web application framework developed with flexibility in mind.</div>

<br />

<div align="center">

[![Discord](https://img.shields.io/discord/837692625737613362.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/refine)
[![Twitter Follow](https://img.shields.io/twitter/follow/refine_dev?style=social)](https://twitter.com/refine_dev)

<a href="https://www.producthunt.com/posts/refine-3?utm_source=badge-top-post-badge&utm_medium=badge&utm_souce=badge-refine&#0045;3" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/top-post-badge.svg?post_id=362220&theme=light&period=daily" alt="refine - 100&#0037;&#0032;open&#0032;source&#0032;React&#0032;framework&#0032;to&#0032;build&#0032;web&#0032;apps&#0032;3x&#0032;faster | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

[![Awesome](https://github.com/refinedev/awesome-refine/raw/main/images/badge.svg)](https://github.com/refinedev/awesome-refine)
[![Maintainability](https://api.codeclimate.com/v1/badges/99a65a191bdd26f4601c/maintainability)](https://codeclimate.com/github/pankod/refine/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/99a65a191bdd26f4601c/test_coverage)](https://codeclimate.com/github/pankod/refine/test_coverage)
[![npm version](https://img.shields.io/npm/v/@pankod/refine-core.svg)](https://www.npmjs.com/package/@pankod/refine-core)
[![npm](https://img.shields.io/npm/dm/@pankod/refine-core)](https://www.npmjs.com/package/@pankod/refine-core)
[![](https://img.shields.io/github/commit-activity/m/refinedev/refine)](https://github.com/refinedev/refine/commits/next)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](CODE_OF_CONDUCT.md)




</div>

<br/>
<a href="https://refine.dev/">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/1110414/197984957-639630c1-03e9-4e18-9a57-63de81124fbd.png">
  <img alt="how-works-refine" src="https://user-images.githubusercontent.com/1110414/197965247-f91f4a0c-f901-4775-b072-abfa736b6e67.png">
</picture>
</a>



## What is refine?
**refine** is a React-based framework for the rapid ✨ development of web applications. 
It eliminates repetitive tasks demanded by **CRUD** operations and provides industry standard solutions for critical parts like **authentication**, **access control**, **routing**, **networking**, **state management**, and **i18n**.

**refine** is *headless by design*, thereby offering unlimited styling and customization options.

## What do you mean by "headless" ?
Instead of being a limited set of pre-styled components, **refine** is a collection of helper `hooks`, `components`, and `providers`. They are all decoupled from *UI components* and *business logic*, so that they never keep you from customizing your *UI* or coding your own flow.

**refine** seamlessly works with any **custom design** or **UI framework** that you favor. For convenience, it ships with ready-made integrations for [Ant Design System](https://ant.design/), [Material UI](https://mui.com/), [Mantine](https://mantine.dev/), and [Chakra UI](https://chakra-ui.com/).

## Use cases
**refine** shines on *data-intensive* applications like *admin panels*, *dashboards* and *internal tools*. Thanks to the built-in **SSR support**, **refine** can also power *customer-facing* applications like *storefronts*.

## Key Features

⚙️ Zero-config, **one-minute setup** with a **single CLI command**

🔌 Connectors for **15+ backend services** including [REST API](https://github.com/refinedev/refine/tree/master/packages/simple-rest), [GraphQL](https://github.com/refinedev/refine/tree/master/packages/graphql), [NestJs CRUD](https://github.com/refinedev/refine/tree/master/packages/nestjsx-crud), [Airtable](https://github.com/refinedev/refine/tree/master/packages/airtable), [Strapi](https://github.com/refinedev/refine/tree/master/packages/strapi), [Strapi v4](https://github.com/refinedev/refine/tree/master/packages/strapi-v4), [Strapi GraphQL](https://github.com/refinedev/refine/tree/master/packages/strapi-graphql), [Supabase](https://github.com/refinedev/refine/tree/master/packages/supabase), [Hasura](https://github.com/refinedev/refine/tree/master/packages/hasura), [Nhost](https://github.com/refinedev/refine/tree/master/packages/nhost), [Appwrite](https://github.com/refinedev/refine/tree/master/packages/appwrite), [Firebase](https://firebase.google.com/), [Directus](https://directus.io/) and [Altogic](https://github.com/refinedev/refine/tree/master/packages/altogic)

🌐 **SSR support** with **Next.js** or **Remix**

⚛ Perfect **state management** & **mutations** with **React Query**

🔀 **Advanced routing** with any router library of your choice

🔐 Providers for seamless **authentication** and **access control** flows

⚡ Out-of-the-box support for **live / real-time applications**

📄 Easy **audit logs** & **document versioning**

💬 Support for any **i18n** framework

💪 Future-proof, **robust architecture**

✅ Full **test coverage**

## Quick Start

The fastest way to get started with **refine** is by using the [superplate](https://github.com/pankod/superplate) project starter tool.
Run the following command to create a new **refine** project configured with  [Ant Design System](https://ant.design/) as the default UI framework:

```
npx superplate-cli --preset refine-antd my-project
```

Once the setup is complete, navigate to the project folder and start your project with:

```
npm run dev
```

Your **refine** application will be accessible at [http://localhost:3000](http://localhost:3000):
<a href="http://localhost:3000">![Welcome on board](https://github.com/refinedev/refine/blob/master/documentation/static/img/welcome-on-board.png?raw=true)</a>
Let's consume a public `fake REST API` and add two resources (*posts*, *categories*) to our project. Replace the contents of `src/App.tsx` with the following code:

```tsx title="src/App.tsx"

import { Refine, useMany } from "@pankod/refine-core";
import {
    useTable,
    List,
    Table,
    DateField,
    Layout,
    ReadyPage,
    notificationProvider,
    ErrorComponent,
} from "@pankod/refine-antd";
import routerProvider from "@pankod/refine-react-router-v6";
import dataProvider from "@pankod/refine-simple-rest";

import "@pankod/refine-antd/dist/styles.min.css";

const App: React.FC = () => {
    return (
        <Refine
            routerProvider={routerProvider}
            dataProvider={dataProvider("https://api.fake-rest.refine.dev")}
            resources={[{ name: "posts", list: PostList }]}
            Layout={Layout}
            ReadyPage={ReadyPage}
            notificationProvider={notificationProvider}
            catchAll={<ErrorComponent />}
        />
    );
};

export const PostList: React.FC = () => {
    const { tableProps } = useTable<IPost>();

    const categoryIds =
        tableProps?.dataSource?.map((item) => item.category.id) ?? [];

    const { data, isLoading } = useMany<ICategory>({
        resource: "categories",
        ids: categoryIds,
        queryOptions: {
            enabled: categoryIds.length > 0,
        },
    });

    return (
        <List>
            <Table<IPost> {...tableProps} rowKey="id">
                <Table.Column dataIndex="title" title="title" />
                <Table.Column
                    dataIndex={["category", "id"]}
                    title="category"
                    render={(value: number) => {
                        if (isLoading) {
                            return "loading...";
                        }

                        return data?.data.find(
                            (item: ICategory) => item.id === value,
                        )?.title;
                    }}
                />
                <Table.Column
                    dataIndex="createdAt"
                    title="createdAt"
                    render={(value) => <DateField format="LLL" value={value} />}
                />
            </Table>
        </List>
    );
};

export default App;

interface IPost {
  title: string;
  createdAt: string;
  category: { id: number };
}

interface ICategory {
  id: number;
  title: string;
}
```

Now, you should see the output as a table populated with `post` & `category` data:
![First example result](https://github.com/refinedev/refine/blob/master/documentation/static/img/first-example-result.png?raw=true)
## Next Steps

👉 Jump to [Refine<>Ant Design Tutorial](https://refine.dev/docs/ui-frameworks/antd/tutorial/) to continue your work and turn the example into a full-blown CRUD application.

👉 Check out the [Refine<>Tailwind Tutorial](https://refine.dev/docs/tutorials/headless-tutorial/) to learn how to use **refine** in a pure *headless* way.

👉 Visit [Learn the Basics Page](https://refine.dev/docs/getting-started/overview/) to get informed about the fundamental concepts.

👉 Read more on [Advanced Tutorials
](https://refine.dev/docs/advanced-tutorials/) for different usage scenarios.

👉 See the real-life [Finefoods Demo](https://refine.dev/demo/) project.

👉 Play with interactive [Examples](https://refine.dev/docs/examples/)

## Roadmap
You can find refine's <a href="https://github.com/refinedev/refine/projects/1">Public Roadmap here!</a> 

## Stargazers

[![Stargazers repo roster for refinedev/refine](https://reporoster.com/stars/refinedev/refine)](https://github.com/refinedev/refine/stargazers)

## Contribution

If you discover a bug, please file a bug report at [issue](https://github.com/refinedev/refine/issues/new?assignees=&labels=bug&template=bug_report.yml&title=%5BBUG%5D). <br/>
If you want to fix a typo or update documentation, raise an issue [here](https://github.com/refinedev/refine/issues/new?assignees=&labels=documentation&template=documentation.yml&title=%5BDOC%5D). <br/>
If you want to propose a feature, raise a detailed issue with explanation [here](https://github.com/refinedev/refine/issues/new?assignees=&labels=enhancement&template=feature_request.yml&title=%5BFEAT%5D).

If you are willing to fix an issue or propose a feature, all PRs with clear explanations are welcome and encouraged.

know more about the ways to contribute [here](https://refine.dev/docs/contributing/#ways-to-contribute)



If you have any doubts related to the project or want to discuss something, then join our [Discord Server](https://discord.gg/refine).


## Our ♥️ Contributors

<a href="https://github.com/refinedev/refine/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=refinedev/refine" />
</a>

## License

Licensed under the MIT License, Copyright © 2021-present Refinedev

