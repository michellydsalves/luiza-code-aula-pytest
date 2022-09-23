# luiza-code-aula-pytest
Exemplos mostrado na aula de pytest do LuizaCode.

# Comandos pytest:

### pytest -v
    Para exibir os testes no modo detalhado.
### pytest -x 
    Para parar no primeiro teste de erro e não rodar tudo
### pytest --pdb 
    Para usar o debbuger

### pytest --junitxml report.xml 
    Para salvar um relatório dos testes (histórico)
### pytest -s
    Para mostrar as saídas no console (print)
### pytest -m multiplo_5
    Para filtar os testes pelo marcador multiplo_5
### pytest -m "not multiplo_5" 
    Para filtar os testes que NÃO estão com o marcador multiplo_5
### pytest --fixtures
    Para listar todas as fixtures do pytest
