# TAC-HUB Contábil — instaladores

Apenas os instaladores e o manifesto assinado do auto-update. O código-fonte é privado.

**Instalar:** baixe o `Instalar_TACHUB_Contabil_vX.Y.Z.exe` da [última versão](../../releases/latest) e abra.
Instala para o seu usuário, sem pedir administrador. Na primeira vez, o Windows pode mostrar
"O Windows protegeu o computador": clique em *Mais informações* → *Executar assim mesmo*.

Depois disso o programa se atualiza sozinho: cada versão traz o `versao.json`, assinado com Ed25519
(`versao.json.sig`), e o programa só instala o que a assinatura e o SHA-256 confirmarem.
