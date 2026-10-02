# PlgMyTailwind

**Tailwind CSS v4 Plugin for LifeTech OCMS**

PlgMyTailwind provides **Tailwind CSS v4** integration for **LifeTech
OCMS**, allowing developers to use Tailwind utility classes when
building LifeTech OCMS themes, modules, plugins, components, layouts,
and views.

The plugin makes it easier to use Tailwind CSS within the LifeTech OCMS
ecosystem.

## Features

-   Tailwind CSS v4 integration
-   Designed specifically for LifeTech OCMS
-   Easy installation through the LifeTech OCMS backend
-   Supports LifeTech themes, modules, and plugins
-   Supports responsive Tailwind utility classes
-   Suitable for developing modern LifeTech OCMS user interfaces

## Installation

There are two recommended ways to install **PlgMyTailwind**.

### Option 1 --- LifeTech OCMS Marketplace

Visit the LifeTech OCMS Marketplace:

https://www.lifetech.host/hubs/community/products?product=plugin

Search for:

``` text
MyTailwind
```

Download the plugin.

Then:

1.  Log in to your **LifeTech OCMS Backend**.
2.  Go to **Packages**.
3.  Select **Plugins**.
4.  Install the downloaded **PlgMyTailwind** package.
5.  Enable or publish the plugin where required.

### Option 2 --- Install Directly from the Backend

LifeTech OCMS can also install supported plugins directly from its
online marketplace.

From your LifeTech OCMS Backend:

1.  Go to **Packages → Plugins**.
2.  Select **Browse Online**.
3.  Search for **MyTailwind**.
4.  Select the plugin.
5.  LifeTech OCMS will download and install the plugin automatically.

## Usage

After installing **PlgMyTailwind**, Tailwind utility classes can be used
in supported LifeTech OCMS content.

``` html
<div class="max-w-4xl mx-auto p-6">
    <div class="rounded-xl shadow-lg p-6">
        <h1 class="text-3xl font-bold">
            Welcome to LifeTech OCMS
        </h1>

        <p class="mt-3 text-gray-600">
            This interface is styled with Tailwind CSS.
        </p>

        <button class="mt-4 px-5 py-2 rounded-lg">
            Get Started
        </button>
    </div>
</div>
```

Tailwind classes can be used when developing:

-   Themes
-   Modules
-   Plugins
-   Components
-   Views
-   Layouts
-   Other supported LifeTech OCMS content

## Theme Development

PlgMyTailwind is particularly useful when developing LifeTech OCMS
themes.

``` html
<section class="container mx-auto px-4 py-10">
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="p-6 rounded-xl shadow">
            <h2 class="text-xl font-semibold">
                LifeTech Component
            </h2>
        </div>
    </div>
</section>
```

This allows LifeTech theme developers to build responsive interfaces
using Tailwind utility classes while keeping application functionality
within LifeTech OCMS.

## Plugin Information

``` text
Package Name: PlgMyTailwind
Package Type: Plugin
Tailwind Version: v4
Framework: LifeTech OCMS
Technology: Tailwind CSS
```

## Repository

https://github.com/ajayi-abolore/PlgMyTailwind

Clone the repository:

``` bash
git clone https://github.com/ajayi-abolore/PlgMyTailwind.git
```

Enter the repository:

``` bash
cd PlgMyTailwind
```

## LifeTech OCMS Documentation

For information about developing themes, modules, plugins, components,
and other packages for LifeTech OCMS:

https://www.lifetech.host/hubs/Docs

## Compatibility

This repository contains the **Tailwind CSS v4** version of
PlgMyTailwind.

Always check the plugin package information and LifeTech OCMS version
requirements before installation.

## Author

**Ajayi Abolore A.**

LifeTech OCMS

https://www.lifetech.host

## License

This project is released under the **MIT License**.

See the `LICENSE` file included in this repository for details.
