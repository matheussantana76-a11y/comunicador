# Pasta de Áudios Reais

Coloque aqui os arquivos de áudio (formato **.mp3**) com a voz real gravada para cada card.

## Como funciona
- O app tenta tocar automaticamente o arquivo `audios/<id>.mp3` de cada card.
- Se o arquivo não existir, ele usa o áudio anexado manualmente pelo botão "Anexar Voz Real" das configurações (se houver).
- Se nenhum dos dois existir, ele fala com a voz sintética do navegador (robótica).

## Nome exato de cada arquivo
O nome do arquivo TEM que ser exatamente o ID do card + `.mp3` (tudo minúsculo, sem espaço, sem acento).

| Arquivo (coloque em `audios/`) | Card | Frase que ele fala |
|---|---|---|
| `banheiro.mp3` | 🚻 Banheiro | "Preciso ir ao banheiro." |
| `sede.mp3` | 💧 Sede / Água | "Estou com sede. Preciso de água." |
| `fome.mp3` | 🍽️ Fome / Comida | "Estou com fome." |
| `remedio.mp3` | 💊 Remédio | "Preciso tomar meu remédio." |
| `dor.mp3` | ⚠️ Dor | "Estou sentindo dor." |
| `ajuda.mp3` | 🆘 Ajuda Urgente | "Preciso de ajuda agora." |
| `sim.mp3` | ✅ Sim | "Sim." |
| `nao.mp3` | ❌ Não | "Não." |
| `frio.mp3` | 🥶 Frio | "Estou com frio. Preciso de uma coberta." |
| `calor.mp3` | 🥵 Calor | "Estou com calor. Pode ligar o ventilador ou ar?" |
| `cansaco.mp3` | 😴 Cansaço | "Estou cansado. Preciso descansar." |
| `posicao.mp3` | 🛏️ Mudar Posição | "Preciso mudar de posição na cama." |
| `sentar.mp3` | 🪑 Quero Sentar | "Quero me sentar um pouco." |
| `deitar.mp3` | 🛌 Quero Deitar | "Quero me deitar." |
| `massagem.mp3` | 💆 Massagem | "Preciso de massagem ou alívio nos músculos." |
| `higiene.mp3` | 🧹 Higiene | "Preciso me limpar ou lavar as mãos." |
| `agua.mp3` | 💧 Água Fresca | "Quero um copo de água fresca." |
| `cafe.mp3` | ☕ Café / Chá | "Quero café ou chá quentinho." |
| `sopa.mp3` | 🥣 Sopa | "Quero comer sopa." |
| `fruta.mp3` | 🍎 Fruta | "Quero comer uma fruta." |
| `suco.mp3` | 🥤 Suco | "Quero um copo de suco." |
| `pao.mp3` | 🥖 Pão / Lanche | "Quero comer um pão ou lanche." |
| `guardanapo.mp3` | 🧻 Guardanapo | "Preciso de um guardanapo, por favor." |
| `satisfeito.mp3` | 🍽️ Satisfeito | "Já estou satisfeito, muito obrigado." |
| `feliz.mp3` | 😀 Feliz | "Estou feliz hoje." |
| `triste.mp3` | 😢 Triste | "Estou me sentindo triste." |
| `ansioso.mp3` | 😰 Ansioso | "Estou ansioso ou preocupado." |
| `saudades.mp3` | 🫂 Saudades | "Estou com saudades de você." |
| `calmo.mp3` | 🤍 Calmo | "Estou calmo e me sentindo bem." |
| `obrigado.mp3` | 🙏 Obrigado | "Muito obrigado por tudo." |
| `teamo.mp3` | ❤️ Te Amo | "Eu amo muito você." |
| `entediado.mp3` | 🥱 Entediado | "Estou um pouco entediado." |
| `rezar.mp3` | 📿 Rezar / Oração | "Gostaria de fazer uma oração." |
| `biblia.mp3` | 📖 Bíblia | "Gostaria de ler ou ouvir a Bíblia." |
| `paz.mp3` | 🕊️ Paz & Silêncio | "Preciso de um momento de paz." |
| `louvor.mp3` | ✨ Louvor | "Gostaria de ouvir uma música religiosa ou louvor." |
| `abencoar.mp3` | 🙌 Abençoar | "Que Deus abençoe você." |
| `tv.mp3` | 📺 Televisão | "Quero ligar ou mudar a TV." |
| `luz.mp3` | 💡 Luz | "Pode acender ou apagar a luz?" |
| `ar.mp3` | ❄️ Ar / Ventilador | "Pode ajustar o ventilador ou ar condicionado?" |
| `janela.mp3` | 🪟 Janela | "Pode abrir ou fechar a janela?" |
| `celular.mp3` | 📱 Celular | "Preciso do meu celular." |
| `silencio.mp3` | 🤫 Silêncio | "Está muito barulho. Preciso de silêncio." |
| `oculos.mp3` | 👓 Óculos | "Preciso dos meus óculos." |
| `socorro.mp3` | 🆘 Socorro Urgente | "Socorro! Preciso de ajuda imediata!" |
| `dor_forte.mp3` | ⚠️ Dor Forte | "Estou sentindo dor." |
| `ar_falta.mp3` | 🫁 Falta de Ar | "Estou com falta de ar. Ajude-me a respirar." |
| `tontura.mp3` | 😵 Tontura | "Estou muito tonto, acho que vou desmaiar." |
| `medico.mp3` | 🚑 Chamar Médico | "Por favor, chame um médico ou emergência." |
| `familia.mp3` | 📞 Ligar pra Família | "Por favor, ligue para a minha família agora." |
| `cai.mp3` | 🩼 Caí / Machuquei | "Eu caí ou me machuquei." |

## Dicas de gravação
- Grave em ambiente silencioso, sem eco (quarto com cortina/tapete ajuda).
- Fale a frase completa, no tom natural, sem pressa.
- Exporte em **MP3**, mono, 128kbps é mais que suficiente (arquivo pequeno = carrega rápido no tablet).
- Nomeie o arquivo exatamente como na tabela acima e coloque nesta pasta.
- Depois de adicionar os arquivos, suba (`git add`, `commit`, `push`) para o GitHub — o GitHub Pages atualiza sozinho.

## Se quiser usar voz de IA em vez de gravação humana
Você pode gerar os áudios uma única vez com um serviço de texto-para-voz natural (ex: ElevenLabs, ou o TTS do Google Cloud/Azure em português-BR), baixar o MP3 de cada frase e salvar aqui com o nome certo. É só fazer isso uma vez — depois o app toca o arquivo pronto, sem precisar gerar de novo.
