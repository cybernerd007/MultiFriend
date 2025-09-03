# MultFriend Me 🎮

**PT-BR** | [English below](#english)

---

## 🇧🇷 Sobre

O **MultFriend Me** é um programa que permite jogar com seus amigos com **interatividade entre todos os jogadores**.  
Simples, divertido e open source!  

---

## 🚀 Instalação (PT-BR)

1. **Instale o [Radmin VPN](https://www.radmin-vpn.com/)**  
   - Crie um grupo/rede no Radmin e adicione todos os jogadores que vão participar.

2. **O host precisa ter o Stream to Earn**  
   - É por ele que a interatividade vai funcionar.

3. **Abra o programa MultFriend Me.**

4. **Conecte usando o IP do host (Radmin) + slug**  
   - Exemplo:  
     ```txt
     meu_ip_do_radmin:8080/event/1
     ```  
   - O número final (`1` no exemplo) corresponde à tecla configurada no **Stream to Earn** (por exemplo, `ALT+1`).  
     `.../event/2` → `ALT+2`, `.../event/3` → `ALT+3`, e assim por diante.

5. **TikFinity – Actions & Events → Trigger Webhook**  
   - No **TikFinity**, vá em **Actions & Events** (ou *Action & Events*) e adicione um **Trigger Webhook**.  
   - **URL do webhook (exemplo):**
     ```txt
     http://SEU_IP_DO_RADMIN:8080/event/1
     ```
   - Associe o webhook ao **evento/gift** que você quiser.  
   - Cada número no final da URL (`/1`, `/2`, `/3`…) dispara a tecla correspondente no **Stream to Earn** (`ALT+1`, `ALT+2`, `ALT+3`…).  
   - **Dica (multi-streamer):** cada streamer pode configurar o próprio TikFinity apontando para o **IP do host** e usar números de evento distintos se quiser separar funções por streamer.

---

## ▶️ Uso (PT-BR)

- Inicie o **MultFriend Me**,  
- Convide seus amigos,  
- E aproveite partidas interativas juntos! 🎉

---

# English 🇺🇸 <a name="english"></a>

---

## 🎮 About

**MultFriend Me** is a program that lets you play with your friends with **full interactivity among all players**.  
Simple, fun, and open source!

---

## 🚀 Installation (EN)

1. **Install [Radmin VPN](https://www.radmin-vpn.com/)**  
   - Create a group/network in Radmin and add all players.

2. **The host must have Stream to Earn**  
   - Interactivity depends on it.

3. **Open the MultFriend Me program.**

4. **Connect using the host’s Radmin IP + slug**  
   - Example:  
     ```txt
     my_radmin_ip:8080/event/1
     ```  
   - The last number (`1` here) maps to the key configured in **Stream to Earn** (e.g., `ALT+1`).  
     `.../event/2` → `ALT+2`, `.../event/3` → `ALT+3`, etc.

5. **TikFinity – Actions & Events → Trigger Webhook**  
   - In **TikFinity**, go to **Actions & Events** and add a **Trigger Webhook**.  
   - **Webhook URL (example):**
     ```txt
     http://YOUR_RADMIN_IP:8080/event/1
     ```
   - Link the webhook to the **event/gift** you want.  
   - Each number at the end of the URL (`/1`, `/2`, `/3`…) triggers the corresponding key in **Stream to Earn** (`ALT+1`, `ALT+2`, `ALT+3`…).  
   - **Tip (multi-streamer):** each streamer can run their own TikFinity pointing to the **host’s IP** and use different event numbers if they want to separate functions per streamer.

---

## 📜 License

MIT License – feel free to fork, modify, and share.
