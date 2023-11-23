# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# A04-Alimentador Automático

## Integrantes: Cleiton Lima, Matheus Adaniya, Wilson Testoni, Gabriel Italo.

## Professores Orientadores: Adriano F. Valente e Victor Bruno.

## Descrição

### Objetivo
Fornecer alimentos seguros e saudáveis, fracionados regularmente para cachorros em situação de rua, tendo em vista a priorização do bem-estar dos animais. Identificar os cães através das fotos feitas pela câmera integrada do ESP32-CAM e fazer o envio das mesmas para ONGs, instituições e petshops parceiros que estejam próximos, assim podendo fazer uma avaliação prévia do estado dos cachorros para que eles possam ser resgatados e tratados.

### O que faz

* Identifica a proximidade do cachorro com o alimentador usando o Sensor de Distância Ultrassônico;<br>
* Uma foto é feita e enviada para a nuvem (Google Drive) pelo ESP32-CAM;<br>
* Libera uma porção de ração feita pelo alimentador, que é composto por um Motor de Passo;<br>
<br>

## 🛠 Estrutura das pastas

-Raiz<br>
|-->documentos<br> 
  &emsp;|-->Projeto-de-extensão-ADS1A-AlimentadorAutomatico3.pdf<br>
|-->imagens<br>
  &emsp;|-->Esquematica_do_trabalho_WOkwI.png<br>
|-->src<br>
  &emsp;  |-->Alimentador-automatico<br>
  &emsp; &emsp; |-->Código_do_Apps_Script_(GoogleDrive)<br>
  &emsp; &emsp; &emsp;|-->Código_Apps_Script<br>
  &emsp; &emsp; |-->alimentador-automatico.ino<br>
  &emsp; &emsp; |-->Base64.cpp<br>
  &emsp; &emsp; |-->Base64.h<br>
  &emsp;  |-->Wokwi<br>
  &emsp; &emsp; |-->Esquematica_do_trabalho_WOkwI.png<br>
  &emsp; &emsp; |-->Link_Wokwi.txt<br>
  
<b>README.MD</b>: Arquivo que serve como guia e explicação geral sobre o projeto.

<b>src</b>: Pasta que contém o código fonte e o link para o Wokwi.

<b>imagens</b>: Imagens da esquemetica do trabalho no Wokwi.

<b>documentos</b>: Todos os documentos do trabalho estão nessa pasta.

## 📋 Licença/License

## 🎓 Referências

Aqui estão as referências usadas no projeto.

1. Sensor de distância: <https://blog.eletrogate.com/sensor-ultrassonico-hc-sr04-com-arduino/>
2. Motor de passo: <https://blog.eletrogate.com/guia-completo-do-motor-de-passo-28byj-48-driver-uln2003/>
3. Pinout ESP32-CAM: <https://randomnerdtutorials.com/esp32-cam-ai-thinker-pinout/#:~:text=The%20ESP32%2DCAM%20comes%20with,CAM%20through%20the%205V%20pin.>
4. Google Drive: <https://www.youtube.com/watch?v=zb7uJlHewAI&ab_channel=UtehStr>
5. Google Drive: <https://www.makerhero.com/blog/tire-fotos-com-esp32-cam-e-armazene-no-google-drive/#:~:text=Depois%20de%20carregado%20o%20c%C3%B3digo,aproximadamente%208%20a%2010%20segundos>


