# Next.js Routes & Nested Routes

## 📁 File Structure

```
/my-next-app
    └── app/
            ├── page.tsx         // Home route
            ├── about/
            │   └── page.tsx     // /about route
            └── blog/
                    ├── page.tsx     // /blog route
                    └── [id]/
                            └── page.tsx // /blog/:id (dynamic route)
```

---

## 🚀 Basic Routing

- Each folder inside `app/` is a route.
- `page.tsx` inside a folder becomes the route's component.

**Example:**  
`app/about/page.tsx` → `/about`

---

## 🧩 Nested Routes

- Create folders inside `app/` for nested routes.
- Each subfolder represents a nested path.

**Example:**  
`app/blog/[id]/page.tsx` → `/blog/123`

---

## 🔄 Dynamic Routes

- Use square brackets `[param]` for dynamic segments.

**Example:**  
`app/user/[username]/page.tsx` → `/user/john`

---

## ✨ Tips

- Use `layout.tsx` for shared layouts in nested routes.
- Organize routes for clarity and scalability.

---

## 📚 References

- [Next.js Routing Docs](https://nextjs.org/docs/app/building-your-application/routing)
