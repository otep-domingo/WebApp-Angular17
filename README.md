# WebApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Running the Project
1. Run your WebAPI in .Net Core 6.0 (using the Visual Studio 2022). Take note of the domain/URL
2. Download the project in your local computer
3. Unzip it and locate the following files:
   - config.json under the src/assets/config folders
       `{
        "apiServer": {
          "url": "https://localhost:7283",
          "version": "v1"
        }
    }`
   - app.module.ts under the src/app folder. Look for this part and update it based on your WebAPI domain
     ` allowedDomains: ["localhost:7283"],`

  ## Important
  1. We are using this GitHub link for the backend https://github.com/otep-domingo/WebAPI
  2. Currently the login uses the
     username: Jaydeep
     Password: Pass@777
3. Follow the tutorial how to make the username/password dynamic.
