# 🎙️ AudioSummary - App para iPhone

Um aplicativo iOS inovador que grava reuniões, aulas, conversas e gera resumos inteligentes automaticamente.

## ✨ Funcionalidades Principais

### 1. 🎙️ Gravação de Áudio
- Grava com alta qualidade (44.1 kHz)
- Timer em tempo real
- Pausa/Retomada
- Armazenamento seguro

### 2. 📋 Resumo Automático
- Extrai pontos-chave da conversa
- Identifica tópicos principais
- Análise de sentimento (Positivo/Negativo/Neutro)

### 3. ❓ Perguntas Inteligentes
- Gera 5 perguntas pertinentes sobre o conteúdo
- Questiona decisões e ações
- Identifica próximos passos

### 4. 📊 Análise Completa
- Resumo estruturado
- Tópicos categorizados
- Sentimento geral da conversa

### 5. 📤 Exportação
- Compartilhe via AirDrop, Email, WhatsApp
- Importe áudios prontos para análise
- Salve resultados localmente

## 🚀 Como Usar

### Setup Inicial
```bash
git clone https://github.com/estherpetrocardoso-debug/AudioSummary.git
cd AudioSummary
open AudioSummary.xcodeproj
```

### No Xcode
1. Selecione um simulador iPhone ou dispositivo físico
2. Clique em ▶️ Run
3. Teste as funcionalidades

## 📁 Estrutura do Projeto

```
AudioSummary/
├── AudioRecorder.swift       # Gravação de áudio
├── AudioProcessor.swift      # Processamento de arquivo
├── ContentAnalyzer.swift     # Análise de conteúdo
├── SummaryGenerator.swift    # Geração de resumos
├── AnalysisView.swift        # Interface de análise
├── RecordingView.swift       # Tela de gravação
├── ContentView.swift         # Tela principal
└── README.md                 # Este arquivo
```

## 🛠️ Requisitos

- iOS 15.0+
- Xcode 13.0+
- Swift 5.5+
- Permissão de Microfone

## 📱 Permissões Necessárias

Adicione ao `Info.plist`:
```xml
<key>NSMicrophoneUsageDescription</key>
<string>Precisamos de acesso ao microfone para gravar conversas</string>
```

## 🎯 Roadmap

- [ ] Transcrição em tempo real (Speech-to-Text)
- [ ] Integração com GPT-4 / Claude
- [ ] Sincronização com iCloud
- [ ] Exportação em PDF
- [ ] Widget do iOS
- [ ] Dark Mode
- [ ] Suporte a múltiplos idiomas

## 📄 Licença

Este projeto está sob a licença MIT.

## 👨‍💻 Autor

Desenvolvido por @estherpetrocardoso-debug

---

**Pronto para revolucionar como você documenta suas conversas! 🚀**