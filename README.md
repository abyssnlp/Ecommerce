# Ecommerce Application

Start strapi installation:

```bash
npx create-strap-app@latest server
```

- `Content-Type Builder`: Create new entries for each collection type (User, Product, Order)
- `Content Manager`: Individual entry of collection types
- `Media Library`: Images, assets
- Marketplace

Ecommerce store collections:

- Item

  - name
  - shortDescription
  - longDescription
  - price
  - image
  - category

- Create Items from the Content Manager
- Client side react app frontend

**Redux**

- Action (to modify state)
- What to perform action on (payload)
- Reducer (updates the state) -> takes in existing State and action
- Redux is immutable

**Strapi**

- Backend for storing collections
- Generates APIs for usage
- Can be done programmatically and via the UI
- Users and roles management
- Authentication and Email support

**Stripe**
For payments with pre-built checkout
