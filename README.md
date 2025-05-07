
## ✅ Pré-requisitos

- Sistema operacional: **Windows**
- **CMake** instalado
- Compilador C++ (ex: MSVC, MinGW)
- **Permissões de administrador** para executar o injetor
- Criar o diretório `C:\\temp` manualmente

## 🚀 Como Usar

1. **Extraia o ZIP**
2. **Execute `run_injection.bat` como administrador** para compilar os projetos
3. Copie a DLL para o caminho `C:\\temp\\test_dll.dll`
4. Abra o `Notepad` manualmente (`notepad.exe`)
5. Execute `injector.exe` (em `build/injector/Release` ou similar)
6. Uma janela de MessageBox será exibida se a injeção for bem-sucedida

## ⚠️ Aviso Legal

> Este projeto é **apenas para uso em laboratório controlado**. Qualquer uso malicioso ou sem autorização explícita pode ser considerado crime conforme leis locais (ex: LGPD, Marco Civil da Internet, CFAA).
> 
> Use com responsabilidade. Você é o único responsável pelo uso do código.

## 📚 Créditos

Desenvolvido como prova de conceito para fins educacionais por Lucas, com suporte de IA.
"""

readme_path = "/mnt/data/README_DLL_Injection_Lab.md"
with open(readme_path, "w") as f:
    f.write(readme_content)

readme_path
