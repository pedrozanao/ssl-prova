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
10.0.2.15 (interface enp0s3 - rede NAT do VirtualBox)

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
