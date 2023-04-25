# **Wallpaper-US**

This repository is dedicated to storing daily wallpapers from Bing, specifically the US version. The wallpapers are sourced from **[Bing](https://www.bing.com/)**'s daily homepage background images.

## **Directory Structure**

```
csharpCopy code
.
├── .github
│   └── workflows
│       └── download.yml
├── src
│   └── index.ts
├── static
│   └── <date>-preview.jpg
├── .gitignore
├── README.md
├── package.json
├── tsconfig.json
└── yarn.lock

```

## **File Descriptions**

- **`.github/workflows/download.yml`**: GitHub Actions workflow file for scheduling and automating the wallpaper download and repository updates from Bing.
- **`src/index.ts`**: Main source code for the wallpaper scraper.
- **`static`**: Folder for storing downloaded wallpaper preview images.
- **`.gitignore`**: Git ignore file configuration.
- **`README.md`**: Project description file.
- **`package.json`**: Project dependencies and related configurations.
- **`tsconfig.json`**: TypeScript configuration file.
- **`yarn.lock`**: Yarn lock file to ensure stable dependency versions.

## **How to Use**

1. Clone this repository:
    
    ```
    bashCopy code
    git clone https://github.com/your_username/wallpaper-US.git
    
    ```
    
2. Install dependencies:
    
    ```
    bashCopy code
    cd wallpaper-US
    yarn install
    
    ```
    
3. Run the scraper:
    
    ```
    sqlCopy code
    yarn start
    
    ```
    
4. After execution, the downloaded wallpapers will be saved in the **`static`** directory.

## **License**

This project is licensed under the **[MIT License](https://opensource.org/licenses/MIT)**.
