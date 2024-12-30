# Configuração do Arduino IDE com Digispark

Este guia descreve como configurar o Arduino IDE para trabalhar com placas Digispark.

## Passo 1: Baixar o Arduino IDE
Baixe o Arduino IDE de uma das seguintes opções:
- [Site oficial](https://www.arduino.cc/en/software)
- [Microsoft Store](https://apps.microsoft.com/store/detail/arduino-ide/9NBLGGH4RSWT)

## Passo 2: Configurar Preferências
1. Abra o Arduino IDE e vá até **File > Preferences**.
2. No campo **Additional Boards Manager URLs**, adicione o seguinte link:
   ```
   https://raw.githubusercontent.com/fellypedarosa/digistump/refs/heads/main/digistump.json
   ```
3. Certifique-se de marcar a opção **Habilitar Dobramento de Código**.

## Passo 3: Instalar ou Atualizar Gerenciadores de Placas
1. Vá até **Tools > Board: "Arduino Uno" > Boards Manager...**.
2. Pesquise por **Arduino AVR Boards** e clique em **Instalar** para instalar ou **Atualizar** para atualizar.
3. Em seguida, pesquise por **Digistump AVR Boards** e clique em **Instalar** para instalar ou **Atualizar** para atualizar.

## Passo 4: Baixar e Instalar os Drivers Digispark
1. Baixe o arquivo de drivers do Digispark:
   - [Digistump Drivers](https://github.com/digistump/DigistumpArduino/releases)
2. Descompacte o arquivo **Digistump.Drivers.zip**.
3. Instale os drivers no seu sistema.

## Passo 5: Baixar ou Atualizar o Java
Certifique-se de que você possui a versão mais recente do Java instalada:
- [Baixar Java](https://www.java.com/pt-BR/download/)

---
Agora o Arduino IDE está configurado para trabalhar com placas Digispark!
