# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# A04-Alimentador Automático

## Integrantes: Cleiton Lima, Matheus Adaniya, Wilson Testoni, Gabriel Italo.

## Professores Orientadores: Adriano F. Valente e Victor Bruno.

### Objetivo
Fornecer alimentos seguros e saudáveis de forma regular para cães em situação de rua, priorizando o bem-estar desses animais. Utilizamos a câmera integrada do ESP32-CAM para capturar imagens dos cães, as quais são enviadas para ONGs, instituições e pet shops parceiros próximos. Essas fotos possibilitam a identificação dos cães, permitindo a avaliação de seu estado físico. Além disso, esse processo auxilia na distinção entre cães que podem ter fugido de seus lares e os que são, de fato, animais de rua, contribuindo para a eficácia do resgate e tratamento.
<br/>

### Como funciona?

* Identifica a proximidade do cachorro com o alimentador usando o Sensor de Distância Ultrassônico.<br>
* Captura uma foto do animal e a envia para a nuvem (Google Drive) através do ESP32-CAM.<br>
* Libera uma porção de ração por meio de um Motor de Passo, componente do alimentador.<br>
<br>

## 🛠 Estrutura das pastas

-Raiz<br>
|-->src<br>
  &emsp;  |-->alimentador-automatico<br>
  &emsp; &emsp; |-->codigo_do_apps_script_(googledrive)<br>
  &emsp; &emsp; &emsp;|-->codigo_apps_script<br>
  &emsp; &emsp; |-->alimentador-automatico.ino<br>
  &emsp; &emsp; |-->Base64.cpp<br>
  &emsp; &emsp; |-->Base64.h<br>
  &emsp;  |-->Wokwi<br>
  &emsp; &emsp; |-->Esquematica_do_trabalho_WOkwI.png<br>
  &emsp; &emsp; |-->estrutura.png<br>
  
<b>README.MD</b>: Arquivo que serve como guia e explicação geral sobre o projeto.

<b>src</b>: Pasta que contém o código fonte e as imagens para um esboço do projeto no Wokwi.

## 🎓 Referências

Aqui estão as referências usadas no projeto.

1. Sensor de distância: <https://blog.eletrogate.com/sensor-ultrassonico-hc-sr04-com-arduino/>
2. Motor de passo: <https://blog.eletrogate.com/guia-completo-do-motor-de-passo-28byj-48-driver-uln2003/>
3. Pinout ESP32-CAM: <https://randomnerdtutorials.com/esp32-cam-ai-thinker-pinout/#:~:text=The%20ESP32%2DCAM%20comes%20with,CAM%20through%20the%205V%20pin.>
4. Google Drive: <https://www.youtube.com/watch?v=zb7uJlHewAI&ab_channel=UtehStr>
5. Google Drive: <https://www.makerhero.com/blog/tire-fotos-com-esp32-cam-e-armazene-no-google-drive/#:~:text=Depois%20de%20carregado%20o%20c%C3%B3digo,aproximadamente%208%20a%2010%20segundos>


