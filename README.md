\documentclass{article}
\usepackage{hyperref}

\title{\textbf{AMA App – Anonymous Messaging with AI Suggestions}}
\author{}
\date{}

\begin{document}

\maketitle

\section*{🚀 Features}
\begin{itemize}
    \item 🔒 \textbf{Anonymous Messaging} – Users can send messages without revealing their identity.
    \item 🤖 \textbf{AI-Powered Suggestions} – Integrated \textbf{OpenAI GPT} to assist users with message generation.
    \item 🔑 \textbf{Secure Authentication} – Implemented with \textbf{NextAuth} for seamless and safe login.
    \item 🗄️ \textbf{Database Management} – Uses \textbf{MongoDB} for efficient data storage.
    \item 🎨 \textbf{Modern UI} – Built with \textbf{Tailwind CSS} for a clean and responsive design.
    \item ✅ \textbf{Data Validation} – Ensures input reliability using \textbf{Zod}.
\end{itemize}

\section*{🛠️ Tech Stack}
\begin{itemize}
    \item \textbf{Frontend \& Backend:} Next.js, TypeScript
    \item \textbf{UI \& Styling:} Tailwind CSS
    \item \textbf{Database:} MongoDB
    \item \textbf{Authentication:} NextAuth
    \item \textbf{AI Integration:} OpenAI GPT
    \item \textbf{Validation:} Zod
\end{itemize}

\section*{📦 Installation \& Setup}
\begin{enumerate}
    \item \textbf{Clone the repository:}  
    \begin{verbatim}
    git clone https://github.com/yourusername/Anonymous_Messaging_App_Using_NextJS.git
    \end{verbatim}

    \item \textbf{Install dependencies:}  
    \begin{verbatim}
    npm install
    \end{verbatim}

    \item \textbf{Set up environment variables:}  
    Create a \texttt{.env.local} file and add the required API keys:  
    \begin{verbatim}
    NEXTAUTH_URL=http://localhost:3000
    MONGODB_URI=your_mongodb_connection_string
    OPENAI_API_KEY=your_openai_api_key
    \end{verbatim}

    \item \textbf{Run the development server:}  
    \begin{verbatim}
    npm run dev
    \end{verbatim}
    The app will be available at \textbf{http://localhost:3000}.
\end{enumerate}


\section*{🛠️ Future Improvements}
\begin{itemize}
    \item ✅ Implement real-time messaging updates
    \item ✅ Enhance AI response personalization
    \item ✅ Add user preferences for AI message suggestions
\end{itemize}

\section*{📜 License}
This project is \textbf{open-source} and available under the \textbf{MIT License}.

\end{document}
