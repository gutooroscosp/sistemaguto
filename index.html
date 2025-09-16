import fetch from 'node-fetch';

export default async function (request, response) {
    const geminiApiKey = process.env.GEMINI_API_KEY; // A sua chave de API será armazenada como uma variável de ambiente no Vercel.

    try {
        // Redireciona a requisição para a API do Gemini
        const geminiResponse = await fetch('https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-image-preview:generateContent?key=' + geminiApiKey, {
            method: 'POST',
            headers: { 'Content-Type': 'application/json' },
            body: JSON.stringify(request.body)
        });

        // Envia a resposta da API de volta para o seu aplicativo
        const data = await geminiResponse.json();
        response.status(geminiResponse.status).json(data);
    } catch (error) {
        response.status(500).json({ error: 'Erro ao processar a requisição.' });
    }
}
