# AZ-900: Tipos de Serviço de Nuvem no Microsoft Azure

Este documento aborda os principais tipos de serviço de nuvem disponíveis no Azure, cada um com características específicas para atender diferentes necessidades de infraestrutura e desenvolvimento.

## Tipos de Serviço de Nuvem

1. **IaaS (Infraestrutura como Serviço)**  
   Permite alugar infraestrutura, como servidores e máquinas virtuais, pagando conforme o uso.
   Aqui o usuario ele tem maior responsabilidade, ou seja ele não ira somente criar o recurso, ele também ira que manter, observar e etc...
   - **Exemplo**: Hospedar um site em um servidor virtual, onde o cliente gerencia o sistema operacional.

3. **PaaS (Plataforma como Serviço)**  
   Oferece um ambiente para desenvolvimento e implantação sem gerenciar a infraestrutura.
   Neste caso aqui pode se dizer que e meio termo de resposabilidade nos recursos.
   - **Exemplo**: Hospedar aplicativos web no Azure App Service sem configurar servidores.

5. **SaaS (Software como Serviço)**  
   O software é entregue pela internet, sem necessidade de instalação local.
   - **Exemplo**: Usar o Microsoft Office 365 através de assinatura online.

6. **Modelo de Responsabilidade Compartilhada**  
   A segurança e gestão do ambiente são divididas entre o cliente e o provedor. Quanto maior o controle do cliente (IaaS), maior sua responsabilidade, enquanto o SaaS reduz essa necessidade.

## Guia de Implementação no Azure

### Criando uma Máquina Virtual no Azure
1. Acesse o **Portal do Azure** > "Máquinas Virtuais" > **"Criar"**.
2. Selecione as configurações de nome, sistema operacional, tamanho e região.
3. Configure a rede e o armazenamento e finalize. Sua VM estará pronta em minutos.

### Configurando uma Instância de Banco de Dados SQL
1. No **Portal do Azure**, selecione "Banco de Dados SQL" > **"Criar"**.
2. Configure nome, servidor e autenticação.
3. Defina as regras de firewall e finalize. Seu banco de dados estará pronto para uso.

Este guia fornece uma introdução prática aos conceitos de IaaS, PaaS e SaaS, além de instruções para configurar máquinas virtuais e bancos de dados no Azure.
