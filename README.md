step 1: npx create-next-app/@latest
step 2: choose 'yes' to {Typescript, Tailwind CSS, App Router} choose 'no' to {ESLint, src directory, alias}
step 3: fix layout.tsx
step 4: Open next.config.js and add:
->const nextConfig = {
output: "export",
images: { unoptimized: true },
};

export default nextConfig;
