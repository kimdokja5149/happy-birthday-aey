# Happy Birthday Card

A Customizable Web based birthday card to wish your friends and family in a unique way.

Check out the [Preview](https://happy-birthday-card.vercel.app/).

If you liked it, please consider giving it star 🤩⭐. Feel free to fork too 🤗.

---

## How to setup

### Remote Deployment

- Vercel Deploy

  [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FAnshumanMahato%2Fvercel-test-hbd&env=NAME,PIC&envDescription=NAME%20-%3E%20Name%20of%20the%20Receiver%20%7C%20PIC%20-%3E%20web%20url%20of%20a%20picture%20of%20the%20receiver&envLink=https%3A%2F%2Fgithub.com%2FAnshumanMahato%2Fvercel-test-hbd%2Fblob%2Fmain%2Fdocs%2Fvariables.md&project-name=happy-birthday-card&repo-name=happy-birthday-card)

- Netlify Deploy

  [![Deploy with NEtlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/AnshumanMahato/vercel-test-hbd)

### For Local Building

1. Clone the repository

   ```sh
   git clone repo-link
   ```

2. Install dependencies

   ```sh
   npm install
   ```

3. Add a pic of the receiver, in the `./local` directory. Ensure that the image is of 1:1 ratio or it might get cropped and squished.

4. Create a `.env` file in root directory, and add the following lines.

   ```env
    NAME='Name of the Receiever'
    PIC='name-of-image.extension'
   ```

5. Execute the following commands in order.

   ```sh
    npm run init-index-local
    npm run build:parcel
   ```

6. Upon Successful execution, your built files will be ready in the `./dist` directory. Open `./dist/index.html` to see the card.

For further customization, checkout [here](./docs/customizations.md).

---

## References

- [Environment Variables](./docs/variables.md)

- [Attributions](./docs/attributions.md)

---

<div align="center">Made with 💖 by Anshuman Mahato</div>
