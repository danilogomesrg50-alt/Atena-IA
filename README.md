                <div class="flex justify-between items-end mb-2">
                    <span class="text-3xl font-bold">OPERACIONAL</span>
                    <span class="text-green-500 text-sm animate-bounce">● Live</span>
                </div>
                <div class="w-full bg-zinc-800 h-1 rounded-full overflow-hidden">
                    <div class="bg-green-500 h-full w-[100%]"></div>
                </div>
            </div>

            <div class="glass-card p-6 rounded-2xl">
                <h3 class="text-xs font-bold text-zinc-500 uppercase mb-4 tracking-widest">Recursos Disponíveis</h3>
                <div class="space-y-4">
                    <div class="flex justify-between">
                        <span class="text-zinc-400 font-medium">Memória Total</span>
                        <span class="text-white font-mono font-bold">81.3 GB</span>
                    </div>
                    <div class="flex justify-between">
                        <span class="text-zinc-400 font-medium">Proprietário</span>
                        <span class="text-white font-bold">Danilo Gomes</span>
                    </div>
                </div>
            </div>

            <a href="mailto:danilosullos@gmail.com" class="block w-full py-4 bg-green-600 hover:bg-green-500 text-black font-black text-center rounded-xl transition-all transform hover:scale-105 shadow-xl">
                CONTRATAR SOLUÇÃO ATENA
            </a>
        </div>

        <div class="lg:col-span-2">
            <div class="terminal-window rounded-xl overflow-hidden shadow-2xl h-[500px] flex flex-col">
                <div id="terminal" class="p-6 text-sm font-mono space-y-2 overflow-y-auto scroll-custom flex-grow">
                    <p class="text-green-400">[SISTEMA] Iniciando interface de monitoramento v7.2...</p>
                    <p class="text-zinc-500">[AUTH] Autenticando Danilo Gomes...</p>
                    <p class="text-blue-400 font-bold">[INFO] Conectando ao repositório GitHub...</p>
                    <p class="text-white">>_</p>
                </div>
            </div>
            <p class="text-[10px] text-zinc-600 mt-4 uppercase tracking-[0.3em] text-center">Monitoramento de Atividade em Tempo Real - Criptografia de Ponta a Ponta</p>
        </div>
    </main>

    <footer class="p-10 border-t border-zinc-900 text-center glass-card">
        <p class="text-zinc-500 text-sm">© 2026 <span class="text-white font-bold">Danilo Gomes</span>. Todos os direitos reservados.</p>
        <p class="text-[10px] text-zinc-700 mt-2">Licenciado para Engenharia de Sistemas de Alta Performance.</p>
    </footer>

    <script>
        const terminal = document.getElementById('terminal');
        const logsIniciais = [
            "🚀 Sistemas de elite iniciados...",
            "🛰️ Vasculhando mercado global de Bounties...",
            "💎 Issue identificada: #9201 - Segurança Crítica",
            "🧠 Groq Llama-3 processando solução lógica...",
            "✅ Patch gerado com sucesso para repositório parceiro",
            "📊 Memória Livre: 81311MB detectados"
        ];

        // Função para simular os logs
        function addLog(msg) {
            const p = document.createElement('p');
            const time = new Date().toLocaleTimeString();
            p.innerHTML = `<span class="text-zinc-600">[${time}]</span> ${msg}`;
            terminal.appendChild(p);
            terminal.scrollTop = terminal.scrollHeight;
        }

        // Loop de simulação (Enquanto o seu servidor está offline ou configurando)
        let i = 0;
        const interval = setInterval(() => {
            if(i < logsIniciais.length) {
                addLog(logsIniciais[i]);
                i++;
            } else {
                addLog("📡 Monitorando novas oportunidades...");
                i = 0; // Reinicia a simulação para manter o site vivo
            }
        }, 4000);
    </script>
</body>
</html>
# Atena-IA
