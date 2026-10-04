# Cenários de Suporte — Cadastro de Clientes

## 1. Cliente não encontrado

**Verificações**
- Nome ou identificador informado corretamente
- Registro realmente cadastrado
- Sessão atual ainda contém os dados
- Limitação de armazenamento apenas em memória

**Conclusão possível:** comportamento esperado por limitação da versão atual.

---

## 2. Dados incorretos no cadastro

**Verificações**
- Entrada informada pelo usuário
- Validações disponíveis
- Campo obrigatório ausente
- Formato inesperado

**Ação:** orientar correção da entrada e registrar necessidade de validação mais robusta.

---

## 3. Dados desapareceram após reiniciar

**Causa esperada:** a versão atual mantém os dados apenas em memória.

**Melhoria planejada:** persistência em banco de dados.

## Como eu explicaria em entrevista

> "Esse projeto me ajuda a mostrar uma diferença importante em suporte: nem todo comportamento relatado pelo usuário é defeito. Às vezes é limitação conhecida, entrada incorreta ou regra do sistema. Eu procuro primeiro classificar corretamente o incidente."
