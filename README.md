# fflgs-comply

Aplicativo Python com Tkinter para analisar o hardware do computador e gerar um `ClientAppSettings.json` de Roblox FastFlags baseado no perfil detectado.

## Como rodar

```powershell
cd C:\Users\Hp\fflgs-comply
python run.py
```

Opcional:

```powershell
pip install -r requirements.txt
```

## Recursos

- Detecta sistema, fabricante, modelo, CPU, RAM, GPU, tela, disco e bateria.
- Classifica o PC em perfil de desempenho.
- Gera `exports\ClientAppSettings.json`.
- Salva relatorios completos em `reports\`.
- Pode instalar o JSON na pasta `ClientSettings` do Roblox com backup do arquivo anterior.
- Tem suporte de deteccao para Windows, Linux e leitura basica em macOS.

## Aviso tecnico

Nenhum gerador consegue garantir 100% de aumento de FPS no Roblox. O ganho real depende de drivers, temperatura, modo de energia, jogo, versao do Roblox e de quais FastFlags o cliente ainda aceita.
