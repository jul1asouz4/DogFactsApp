# 🐶 Dog Facts App

Aplicação simples em **C# (.NET)** que consome a **API pública Dog CEO** para exibir imagens e informações de cães.

---

## 🔗 API utilizada
- **URL base:** https://dog.ceo/api/breeds/image/random  
- **Documentação:** https://dog.ceo/dog-api/

A API retorna uma imagem aleatória de um cão, e podemos extrair a raça a partir da URL da imagem.

---

## 📦 Campos extraídos
- `message`: URL da imagem do cão  
- `status`: estado da requisição  
- `breed`: nome da raça (extraída da URL da imagem)

---

## 🚀 Como executar

1. Certifique-se de ter o **.NET 8 SDK** instalado.
2. No terminal, execute:
   ```bash
   dotnet run
