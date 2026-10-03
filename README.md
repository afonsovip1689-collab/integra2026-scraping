# integra2026-scraping
main.py
# Extração de palestrantes - Integra IF Goiano 2026

Projeto da disciplina de Linguagens Formais e Autômatos (Eng. de Computação - IF Goiano, Câmpus Trindade).

Automação em Python que baixa a página de eventos, extrai com **expressões regulares** imagem, nome, local de trabalho e contato dos palestrantes, baixa as fotos e grava tudo em SQLite.

## Execução

```bash
python main.py              # baixa a página e executa todas as tarefas
python main.py --offline    # usa o pagina.txt existente, sem baixar o HTML
python verificar.py        # confere banco, imagens e contagem
