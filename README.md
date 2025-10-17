<!DOCTYPE html>
<html lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Legal Firm Document Management</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet"/>
<script>
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              primary: "#1773cf",
              "background-light": "#f6f7f8",
              "background-dark": "#111921",
              "foreground-light": "#111827",
              "foreground-dark": "#f9fafb",
              "border-light": "#e5e7eb",
              "border-dark": "#374151",
              "muted-light": "#6b7280",
              "muted-dark": "#9ca3af",
            },
            fontFamily: {
              display: ["Manrope", "sans-serif"],
            },
            borderRadius: {
              DEFAULT: "0.25rem",
              lg: "0.5rem",
              xl: "0.75rem",
              full: "9999px",
            },
          },
        },
      };
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: "FILL" 0, "wght" 400, "GRAD" 0, "opsz" 24;
      }
    </style>
</head>
<body class="bg-background-light dark:bg-background-dark font-display">
<div class="flex min-h-screen">
<aside class="w-64 bg-background-light dark:bg-background-dark border-r border-border-light dark:border-border-dark flex flex-col">
<div class="p-6">
<h1 class="text-xl font-bold text-foreground-light dark:text-foreground-dark">Apex Legal</h1>
</div>
<nav class="flex-1 px-4 py-2 space-y-1">
<a class="flex items-center gap-3 px-4 py-2 rounded text-foreground-light dark:text-foreground-dark hover:bg-primary/10 dark:hover:bg-primary/20" href="#">
<span class="material-symbols-outlined">dashboard</span>
<span class="text-sm font-medium">Dashboard</span>
</a>
<a class="flex items-center gap-3 px-4 py-2 rounded text-foreground-light dark:text-foreground-dark hover:bg-primary/10 dark:hover:bg-primary/20" href="#">
<span class="material-symbols-outlined">group</span>
<span class="text-sm font-medium">Clients</span>
</a>
<a class="flex items-center gap-3 px-4 py-2 rounded text-foreground-light dark:text-foreground-dark hover:bg-primary/10 dark:hover:bg-primary/20" href="#">
<span class="material-symbols-outlined">work</span>
<span class="text-sm font-medium">Cases</span>
</a>
<a class="flex items-center gap-3 px-4 py-2 rounded bg-primary text-white" href="#">
<span class="material-symbols-outlined !font-normal">folder</span>
<span class="text-sm font-medium">Documents</span>
</a>
<a class="flex items-center gap-3 px-4 py-2 rounded text-foreground-light dark:text-foreground-dark hover:bg-primary/10 dark:hover:bg-primary/20" href="#">
<span class="material-symbols-outlined">request_quote</span>
<span class="text-sm font-medium">Billing</span>
</a>
</nav>
<div class="px-4 py-2">
<a class="flex items-center gap-3 px-4 py-2 rounded text-foreground-light dark:text-foreground-dark hover:bg-primary/10 dark:hover:bg-primary/20" href="#">
<span class="material-symbols-outlined">settings</span>
<span class="text-sm font-medium">Settings</span>
</a>
</div>
</aside>
<main class="flex-1 p-8">
<header class="flex items-center justify-between mb-8">
<h2 class="text-3xl font-bold text-foreground-light dark:text-foreground-dark">Document Management</h2>
<div class="flex items-center gap-4">
<button class="bg-primary/10 dark:bg-primary/20 text-primary px-4 py-2 rounded-lg flex items-center gap-2">
<span class="material-symbols-outlined">mail</span>
                Email Automations
              </button>
<button class="bg-primary text-white px-4 py-2 rounded-lg flex items-center gap-2">
<span class="material-symbols-outlined">upload_file</span>
                Upload Document
              </button>
</div>
</header>
<div class="mb-6">
<div class="relative">
<span class="material-symbols-outlined absolute left-3 top-1/2 -translate-y-1/2 text-muted-light dark:text-muted-dark">search</span>
<input class="w-full pl-10 pr-4 py-2 rounded-lg bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark focus:ring-primary focus:border-primary text-foreground-light dark:text-foreground-dark placeholder-muted-light dark:placeholder-muted-dark" placeholder="Search documents..." type="text"/>
</div>
</div>
<div class="border-b border-border-light dark:border-border-dark mb-6">
<nav class="flex space-x-8">
<a class="pb-3 border-b-2 border-primary text-primary font-semibold" href="#">All Documents</a>
<a class="pb-3 border-b-2 border-transparent text-muted-light dark:text-muted-dark hover:text-primary hover:border-primary" href="#">Client Documents</a>
<a class="pb-3 border-b-2 border-transparent text-muted-light dark:text-muted-dark hover:text-primary hover:border-primary" href="#">Firm Documents</a>
<a class="pb-3 border-b-2 border-transparent text-muted-light dark:text-muted-dark hover:text-primary hover:border-primary" href="#">Sent Emails</a>
</nav>
</div>
<div class="overflow-x-auto bg-background-light dark:bg-background-dark rounded-lg border border-border-light dark:border-border-dark">
<table class="w-full text-sm text-left text-foreground-light dark:text-foreground-dark">
<thead class="bg-background-light dark:bg-background-dark border-b border-border-light dark:border-border-dark">
<tr>
<th class="px-6 py-3 font-medium" scope="col">Document Name</th>
<th class="px-6 py-3 font-medium" scope="col">Category</th>
<th class="px-6 py-3 font-medium" scope="col">Uploaded By</th>
<th class="px-6 py-3 font-medium" scope="col">Date Uploaded</th>
<th class="px-6 py-3 font-medium" scope="col">Email Status</th>
<th class="px-6 py-3 font-medium" scope="col">Last Modified</th>
<th class="px-6 py-3 font-medium" scope="col">Modified By</th>
<th class="px-6 py-3 font-medium" scope="col">Version</th>
<th class="px-6 py-3 font-medium text-right" scope="col">Actions</th>
</tr>
</thead>
<tbody>
<tr class="border-b border-border-light dark:border-border-dark">
<td class="px-6 py-4 font-medium">Contract Agreement</td>
<td class="px-6 py-4"><span class="px-2 py-1 text-xs font-medium rounded-full bg-primary/10 text-primary dark:bg-primary/20">Contracts</span></td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">John Doe</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">2024-03-10</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark"><span class="inline-flex items-center px-2 py-1 text-xs font-medium rounded-full bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-300">Sent</span></td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">2024-03-15</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">John Doe</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">v2.1</td>
<td class="px-6 py-4 text-right space-x-4">
<a class="font-medium text-primary hover:underline" href="#">Send</a>
<a class="font-medium text-primary hover:underline" href="#">View</a>
</td>
</tr>
<tr class="border-b border-border-light dark:border-border-dark">
<td class="px-6 py-4 font-medium">Client Intake Form</td>
<td class="px-6 py-4"><span class="px-2 py-1 text-xs font-medium rounded-full bg-primary/10 text-primary dark:bg-primary/20">Forms</span></td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">Jane Smith</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">2024-04-18</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark"><span class="inline-flex items-center px-2 py-1 text-xs font-medium rounded-full bg-yellow-100 text-yellow-800 dark:bg-yellow-900 dark:text-yellow-300">Pending</span></td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">2024-04-20</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">Jane Smith</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">v1.5</td>
<td class="px-6 py-4 text-right space-x-4">
<a class="font-medium text-primary hover:underline" href="#">Send</a>
<a class="font-medium text-primary hover:underline" href="#">View</a>
</td>
</tr>
<tr class="border-b border-border-light dark:border-border-dark">
<td class="px-6 py-4 font-medium">Legal Research Report</td>
<td class="px-6 py-4"><span class="px-2 py-1 text-xs font-medium rounded-full bg-primary/10 text-primary dark:bg-primary/20">Research</span></td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">Admin</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">2024-05-08</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark"><span class="inline-flex items-center px-2 py-1 text-xs font-medium rounded-full bg-gray-100 text-gray-800 dark:bg-gray-700 dark:text-gray-300">Not Sent</span></td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">2024-05-10</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">Admin</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">v3.0</td>
<td class="px-6 py-4 text-right space-x-4">
<a class="font-medium text-primary hover:underline" href="#">Send</a>
<a class="font-medium text-primary hover:underline" href="#">View</a>
</td>
</tr>
<tr class="border-b border-border-light dark:border-border-dark">
<td class="px-6 py-4 font-medium">Court Filing</td>
<td class="px-6 py-4"><span class="px-2 py-1 text-xs font-medium rounded-full bg-primary/10 text-primary dark:bg-primary/20">Filings</span></td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">Michael Brown</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">2024-06-02</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark"><span class="inline-flex items-center px-2 py-1 text-xs font-medium rounded-full bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-300">Sent</span></td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">2024-06-05</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">Michael Brown</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">v1.2</td>
<td class="px-6 py-4 text-right space-x-4">
<a class="font-medium text-primary hover:underline" href="#">Send</a>
<a class="font-medium text-primary hover:underline" href="#">View</a>
</td>
</tr>
<tr>
<td class="px-6 py-4 font-medium">Invoice</td>
<td class="px-6 py-4"><span class="px-2 py-1 text-xs font-medium rounded-full bg-primary/10 text-primary dark:bg-primary/20">Billing</span></td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">Jessica White</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">2024-05-30</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark"><span class="inline-flex items-center px-2 py-1 text-xs font-medium rounded-full bg-red-100 text-red-800 dark:bg-red-900 dark:text-red-300">Failed</span></td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">2024-06-01</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">Jessica White</td>
<td class="px-6 py-4 text-muted-light dark:text-muted-dark">v1.0</td>
<td class="px-6 py-4 text-right space-x-4">
<a class="font-medium text-primary hover:underline" href="#">Send</a>
<a class="font-medium text-primary hover:underline" href="#">View</a>
</td>
</tr>
</tbody>
</table>
</div>
</main>
</div>

</body></html>
