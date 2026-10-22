# YardPro — downloads para macOS

Todas as suas IAs de código num lugar só. Página oficial: https://yard-pro.dev/download

## Instalar

1. Baixe o `.dmg` do [último release](https://github.com/gabrielssoares582/yard-pro-releases/releases/latest):
   - **Apple Silicon (M1–M4):** `YardPro-mac-arm64.dmg`
   - **Intel:** `YardPro-mac-x64.dmg`
2. Abra o `.dmg` e arraste o **YardPro** para **Aplicativos**.
3. O YardPro ainda não tem assinatura da Apple (Developer ID). Na primeira vez, libere o app com um comando no Terminal:

   ```sh
   xattr -dr com.apple.quarantine /Applications/YardPro.app
   ```

   Ou: Ajustes do Sistema › Privacidade e Segurança › "Abrir mesmo assim".

Cada release traz o `SHA256SUMS` para você conferir o arquivo baixado.
