# Skytap-Was
# GUIA DE INSTALACIÓN DE WEBSPHERE APPLICATION SERVER LIBERTY EN SKYTAP

_Para el desarrollo de este Despliegue se tiene como base una maquina Ubuntu 18.04.1 que se encuentra alojada en Skytap._

Indice


## Instalación del IBM Instalation Manager: 🚀

### Descargue a la maquina Ubuntu el instalador de IBM IM

_Inicialmente debe acceder al shell de IBM Cloud desde el siguiente link:_
```
https://www.ibm.com/support/fixcentral/swg/downloadFixes?parent=ibm~Rational&product=ibm/Rational/IBM+Installation+Manager&release=All&platform=All&function=fixId&fixids=1.8.2.0-IBMIM-LINUX-X86_64-20150303_1526&includeRequisites=1&includeSupersedes=0&downloadMethod=http
```
<img width="439" alt="IBMIM" src="https://user-images.githubusercontent.com/60987042/83689743-33815900-a5b5-11ea-84a6-40a486002b4c.PNG">


### Instalar en la maquina ubuntu el Installation Manager de IBM 📦


_1.	Debemos abrir una terminal, la cual se puede abrir mediante el siguiente comando:_

```
Crtl+Alt+T
```
<img width="551" alt="term" src="https://user-images.githubusercontent.com/60987042/83689785-45fb9280-a5b5-11ea-9474-639a35eaee67.PNG">

_2. Debemos dirigirnos a la capeta en la cual se descargo el instalador._

```
cd Desktop
```
ó
```
cd Descargas
```

_3.	Ahora debemos descomprimir el archivo que se descargo:_

```
unzip agent.installer.linux.gtk.x86_64_1.8.2000.20150303_1526.zip
```

_4. Ahora debemos ejecutar el comando de intalacion	:_

```
./install
```

_5.	Al ejecutar el comando anterior se nos debe ejecutar una insterfaz grafica de instalación en la cual debemos dar clic en **NEXT**:_

<img width="443" alt="installa" src="https://user-images.githubusercontent.com/60987042/83689938-7ba07b80-a5b5-11ea-8a51-3956488ba23c.PNG">

_6.	Debemos Aceptar los terminos y condiciones de la licencia y luego hacer clic en **NEXT**:_

<img width="443" alt="Terminos" src="https://user-images.githubusercontent.com/60987042/83689965-86f3a700-a5b5-11ea-8670-3cb28fd784bb.PNG">

_7.	Ahora debemos elegir la direccion de almacenamiento en la cual se va instalar, de forma predeterminada, se instalará en /opt/IBM; sin embargo, si lo desea, puede cambiar la ruta de instalación haciendo clic en Examinar:_

<img width="441" alt="ruta" src="https://user-images.githubusercontent.com/60987042/83689999-9246d280-a5b5-11ea-8ce2-0de038bf702f.PNG">

_8.	Despues de aceptar los terminos, condiciones y seleccionar la ruta de instalción debemos dar clic en **Install**:_

<img width="442" alt="Installfinal" src="https://user-images.githubusercontent.com/60987042/83690057-a4c10c00-a5b5-11ea-87f1-2908ef623c3c.PNG">

_9.	Por ultimo debemos verificar si el Installation Manager de IBM quedo correctamente instalado, para esto debemos dar clic en reiniciar y se debe abrir automaticamente:_

<img width="444" alt="verify" src="https://user-images.githubusercontent.com/60987042/83690081-b0143780-a5b5-11ea-87fe-b58d78a4fe97.PNG">

