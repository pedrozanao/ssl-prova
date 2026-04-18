# ssl-prova
Atividade Prática - SSL e Certificados Digitais
# SSL e Certificados Digitais – Atividade Prática

## Aluno
Pedro Afonso Zanão

## Ambiente
- Sistema Operacional: Debian 
- Virtualização: VirtualBox
- Ferramenta principal: OpenSSL

## IP utilizado
192.168.56.1 (Local da máquina)

## Dificuldades Encontradas
- O login root via SSH estava desabilitado por padrão no Debian 13,
  sendo necessário editar o arquivo /etc/ssh/sshd_config para permitir
  a autenticação e conseguir realizar a transferência SCP.
- O servidor embutido do Python não suporta HTTPS nativamente,
  o que exigiu a compreensão da diferença entre HTTP e HTTPS na prática.

## Conclusão
A atividade permitiu compreender na prática o ciclo completo de uma
infraestrutura de chave pública: geração de chave privada, criação de
requisição de certificado (CSR), emissão de certificado auto-assinado,
transferência segura via SCP e validação. 
