# Source Code Structure

This directory contains all the source code for the ENKI Reality Admin Panel.

## Directory Structure

```
src/
├── components/       # Reusable UI components
│   ├── ui/          # Base UI components (buttons, forms, etc.)
│   ├── layout/      # Layout components (sidebar, header, etc.)
│   └── features/    # Feature-specific components
├── pages/           # Page components (routes)
│   ├── Dashboard/   # Dashboard page
│   ├── Properties/  # Properties management
│   ├── Projects/    # Projects management
│   └── ...          # Other pages
├── hooks/           # Custom React hooks
├── lib/            # Library configurations
│   ├── supabase.ts # Supabase client
│   └── utils.ts    # Utility functions
├── styles/         # Global styles
├── types/          # TypeScript type definitions
├── i18n/          # Internationalization
├── App.tsx        # Main App component
└── main.tsx       # Application entry point
```

## Key Files

- `App.tsx` - Main application component with routing
- `main.tsx` - Application entry point
- `lib/supabase.ts` - Supabase client configuration
- `types/index.ts` - Main TypeScript definitions
