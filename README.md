# Playwright + POM + cucumberJS + Allure

Esta es una implementación  de Playwright + POM + cucumberJS + Allure con varios tipos de reportes

1. Debe instalar las librerias de npm
```bash
  npm install
```
2. se puede ejecutar las pruebas de 2 formas
- para ver la ejecucion en la consola
```bash
  npm run test
```
- para poder obtener el resultados con allure report
```bash
  npm test:allure
```
3. se puede obtener los reporter de diferentes maneras
- ejecuta la libreria cucumber-html-reporter para obtener el reporte html de esa libreria
```bash
  npm run report-simple-cucumber

```
- ejecuta la libreria multiple-cucumber-html-reporter para obtener el reporte html de esa libreria
```bash
  npm run report-multiple-cucumber

```
- ejecuta la generacion de los resultados para allure report
```bash
  npm run allure-generate

```
- abre el reporte de allure report en un puerto que se muestra en consola
```bash
  npm run allure-open

```

todos los reportes en formato html se guardar en la carpeta 
```bash
  test-results/

```
