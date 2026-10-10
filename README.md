<!DOCTYPE html>
<lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Titulaciones Ácido-Base UNLC</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
      body { font-family: 'Inter', sans-serif; background-color: #0f172a; color: #f8fafc; }
      /* Custom scrollbar for dark theme */
      ::-webkit-scrollbar {
        width: 8px;
      }
      ::-webkit-scrollbar-track {
        background: #1e293b; 
      }
      ::-webkit-scrollbar-thumb {
        background: #475569; 
        border-radius: 4px;
      }
      ::-webkit-scrollbar-thumb:hover {
        background: #64748b; 
      }

      @keyframes dropFall {
        0% {
          transform: translate(-50%, 0) scale(0.7, 1.25);
          opacity: 0.95;
        }
        20% {
          transform: translate(-50%, calc(var(--target-y, 240px) * 0.16)) scale(0.85, 1.4);
          opacity: 1;
        }
        60% {
          transform: translate(-50%, calc(var(--target-y, 240px) * 0.58)) scale(0.95, 1.3);
          opacity: 1;
        }
        92% {
          transform: translate(-50%, calc(var(--target-y, 240px) * 0.95)) scale(1.05, 0.95);
          opacity: 0.95;
        }
        100% {
          transform: translate(-50%, var(--target-y, 240px)) scale(1.3, 0.25);
          opacity: 0;
        }
      }

      @keyframes sampleWave {
        0% {
          width: 6px;
          height: 2px;
          opacity: 0.95;
          transform: translate(-50%, -50%) scale(1);
        }
        30% {
          opacity: 0.9;
        }
        70% {
          opacity: 0.55;
        }
        100% {
          width: 72px;
          height: 16px;
          opacity: 0;
          transform: translate(-50%, -50%) scale(1.15);
        }
      }

      @keyframes splashBead {
        0% {
          transform: translate(-50%, 0);
          opacity: 0.95;
        }
        50% {
          transform: translate(-50%, -8px);
          opacity: 1;
        }
        100% {
          transform: translate(-50%, 0);
          opacity: 0;
        }
      }
    </style>
  <script type="importmap">
{
  "imports": {
    "react/": "https://aistudiocdn.com/react@^19.2.0/",
    "react": "https://aistudiocdn.com/react@^19.2.0",
    "react-dom/": "https://aistudiocdn.com/react-dom@^19.2.0/",
    "@google/genai": "https://aistudiocdn.com/@google/genai@^1.30.0",
    "lucide-react": "https://aistudiocdn.com/lucide-react@^0.554.0"
  }
}
</script>
<link rel="stylesheet" href="/index.css">
</head>
  <body>
    <div id="root"></div>
  <script type="module" src="/index.tsx"></script>
</body>
</html>
