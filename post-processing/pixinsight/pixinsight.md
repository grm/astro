# PixInsight processing

## Image integration

- Enable drizzle data on light frames

## DrizzleIntegration 

> Can be found under `PROCESS -> Image Integration -> DrizzleIntegratrion`

For each master files produced by the integration, you can integrate drizzle data if :
- the images are undersampled
- you made some dithering during pictures

To configure the process, you have to configure accordingly the process by addding all `.xdrz` files that have been produced during the integration (they should be located under `<your pixinsight working directory>/registered`) :

 ![Drizzle integration configuration](img/drizzle_configuration.png)

 To launch the process click on the round button to apply the process.

 Ho, and get grab a coffee ;) 