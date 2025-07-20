# 📿 e-Missal - Sistema de Ordem da Missa

Sistema web para gerenciar a ordem da missa com cânticos, timer e funcionalidades de salvar/carregar configurações.

## 🚀 Funcionalidades

### ⏱️ Timer
- **Start**: Inicia o cronômetro da missa
- **Stop**: Para o cronômetro
- **Reset**: Zera o cronômetro

### 🎵 Gerenciamento de Cânticos
- **Adicionar**: Clique no botão "+" para adicionar novos cânticos
- **Editar**: Clique no ícone ✏️ para editar um cântico
- **Excluir**: Clique no ícone 🗑️ para remover um cântico
- **Marcar como Realizado**: Clique no cântico para movê-lo para a lista de realizados
- **Reorganizar**: Arraste e solte os cânticos para reordená-los

### 💾 Sistema de Salvar/Carregar
- **Salvar**: Clique em "💾 Salvar" para salvar a configuração atual com um nome personalizado
- **Carregar**: Clique em "📂 Carregar" para ver e carregar configurações salvas anteriormente
- **Excluir Configurações**: Na tela de carregar, use o ícone 🗑️ para excluir configurações salvas

## 🎼 Tipos de Cânticos Disponíveis
- Entrada
- Ato Penitencial
- Glória
- Salmo Responsorial
- Aclamação ao Evangelho
- Apresentação das Oferendas
- Santo
- Cordeiro de Deus
- Comunhão
- Ação de Graças
- Final
- Meditação
- Adoração

## 🎹 Tons Musicais Suportados
Todos os tons maiores e menores:
- C, Cm, C#, C#m, Db, Dbm
- D, Dm, D#, D#m, Eb, Ebm
- E, Em, F, Fm, F#, F#m
- Gb, Gbm, G, Gm, G#, G#m
- Ab, Abm, A, Am, A#, A#m
- Bb, Bbm, B, Bm

## 💾 Banco de Dados
O sistema utiliza:
- **LocalStorage** do navegador para armazenamento local
- **database.json** como estrutura de referência para o banco de dados

### Estrutura dos Dados Salvos
```json
{
  "id": 1642678800000,
  "nome": "Missa de Domingo",
  "data": "20/01/2025 10:30:00",
  "canticos": [...],
  "realizados": [...],
  "timer": {
    "elapsedTime": 0,
    "isRunning": false
  }
}
```

## 🎨 Design
- Interface responsiva (desktop e mobile)
- Tema escuro com gradientes
- Efeitos visuais modernos (blur, sombras)
- Animações suaves
- Fonte Ubuntu Mono

## 🔧 Como Usar

1. **Abra o arquivo `e-Missal.html` no navegador**
2. **Adicione cânticos** clicando no botão "+"
3. **Organize a ordem** arrastando os cânticos
4. **Inicie o timer** quando começar a missa
5. **Marque cânticos como realizados** clicando neles
6. **Salve a configuração** para uso futuro

## 📱 Compatibilidade
- Chrome, Firefox, Safari, Edge
- Dispositivos móveis e tablets
- Funciona offline após o primeiro carregamento

## 🔄 Atualizações
- Versão 1.0: Sistema básico com timer e cânticos
- Versão 1.1: Adicionado sistema de salvar/carregar configurações
- Banco de dados JSON para estruturação dos dados

## 👨‍💻 Desenvolvido por
Sistema criado para facilitar o gerenciamento da ordem da missa com interface moderna e intuitiva.

