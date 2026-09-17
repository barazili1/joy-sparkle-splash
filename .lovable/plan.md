# Confirm Simulation screen

## What will be built
- Add a new `/confirm-simulation` screen matching the supplied Arabic transfer confirmation reference.
- Recreate the full-height purple/orange background, amount and fee summary, sender and wallet cards, transfer connector, IPN mark, and bottom confirmation controls.
- Use the existing National Bank and IPN artwork, plus the wallet icon cropped from the supplied reference.
- Connect the transfer form’s “التالي” button to the new screen and carry across the entered phone number and amount.
- Make the back control return to the transfer form and preserve the entered values where possible.

## Technical details
- Keep temporary transfer details in URL search parameters so the screen works without a backend.
- Add route-specific title, description, Open Graph, and Twitter metadata.
- Add responsive styles using the project’s existing Instapay design tokens and verify the flow at mobile dimensions.
