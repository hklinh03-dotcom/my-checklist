<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Checklist của tôi ✨</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Crimson+Pro:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Crimson Pro', serif;
            background: linear-gradient(135deg, #FAF8F3 0%, #F5F1E8 100%);
            min-height: 100vh;
            padding: 2rem 1rem;
            color: #3D3226;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
        }

        header {
            text-align: center;
            margin-bottom: 2.5rem;
        }

        h1 {
            font-size: 2.5rem;
            color: #5D4E37;
            margin-bottom: 0.5rem;
            font-weight: 600;
        }

        .subtitle {
            color: #8B7355;
            font-size: 1.1rem;
        }

        .tabs {
            display: flex;
            gap: 1rem;
            margin-bottom: 2rem;
            border-bottom: 2px solid #E8DCC8;
            overflow-x: auto;
            padding-bottom: 0.5rem;
        }

        .tab {
            background: none;
            border: none;
            padding: 0.75rem 1.5rem;
            font-family: 'Crimson Pro', serif;
            font-size: 1.1rem;
            color: #8B7355;
            cursor: pointer;
            transition: all 0.3s;
            white-space: nowrap;
            position: relative;
        }

        .tab:hover {
            color: #5D4E37;
        }

        .tab.active {
            color: #5D4E37;
            font-weight: 600;
        }

        .tab.active::after {
            content: '';
            position: absolute;
            bottom: -0.6rem;
            left: 0;
            right: 0;
            height: 3px;
            background: #C9A87C;
            border-radius: 2px;
        }

        .tab-content {
            display: none;
        }

        .tab-content.active {
            display: block;
            animation: fadeIn 0.3s;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .dashboard {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin-bottom: 2rem;
        }

        .stat-card {
            background: rgba(255, 255, 255, 0.7);
            border: 2px solid #E8DCC8;
            border-radius: 16px;
            padding: 1.5rem;
            text-align: center;
            transition: transform 0.2s;
        }

        .stat-card:hover {
            transform: translateY(-3px);
        }

        .stat-number {
            font-size: 2.5rem;
            font-weight: 600;
            color: #5D4E37;
            margin-bottom: 0.5rem;
        }

        .stat-label {
            color: #8B7355;
            font-size: 1rem;
        }

        .add-task-container {
            background: rgba(255, 255, 255, 0.7);
            border: 2px solid #E8DCC8;
            border-radius: 16px;
            padding: 1.5rem;
            margin-bottom: 2rem;
        }

        .task-input-group {
            display: flex;
            gap: 0.75rem;
            margin-bottom: 1rem;
        }

        input[type="text"] {
            flex: 1;
            padding: 0.875rem 1.25rem;
            border: 2px solid #E8DCC8;
            border-radius: 12px;
            font-family: 'Crimson Pro', serif;
            font-size: 1rem;
            background: white;
            color: #3D3226;
            transition: border-color 0.3s;
        }

        input[type="text"]:focus {
            outline: none;
            border-color: #C9A87C;
        }

        .btn {
            padding: 0.875rem 1.75rem;
            background: #C9A87C;
            color: white;
            border: none;
            border-radius: 12px;
            font-family: 'Crimson Pro', serif;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
        }

        .btn:hover {
            background: #B89766;
            transform: translateY(-2px);
        }

        .btn:active {
            transform: translateY(0);
        }

        .task-list {
            display: flex;
            flex-direction: column;
            gap: 0.75rem;
        }

        .task-item {
            background: white;
            border: 2px solid #E8DCC8;
            border-radius: 12px;
            padding: 1rem 1.25rem;
            display: flex;
            align-items: center;
            gap: 1rem;
            transition: all 0.3s;
        }

        .task-item:hover {
            border-color: #C9A87C;
        }

        .task-item.completed {
            opacity: 0.6;
            background: #FDFBF7;
        }

        .task-item.completed .task-text {
            text-decoration: line-through;
            color: #8B7355;
        }

        .checkbox {
            width: 24px;
            height: 24px;
            border: 2px solid #C9A87C;
            border-radius: 6px;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
            transition: all 0.3s;
        }

        .checkbox:hover {
            background: #FFF9F0;
        }

        .checkbox.checked {
            background: #C9A87C;
        }

        .checkbox.checked::after {
            content: '✓';
            color: white;
            font-size: 16px;
            font-weight: bold;
        }

        .task-text {
            flex: 1;
            font-size: 1.05rem;
            color: #3D3226;
        }

        .delete-btn {
            background: none;
            border: none;
            color: #D4A574;
            font-size: 1.3rem;
            cursor: pointer;
            padding: 0.25rem 0.5rem;
            opacity: 0.6;
            transition: opacity 0.3s;
        }

        .delete-btn:hover {
            opacity: 1;
            color: #C9A87C;
        }

        .empty-state {
            text-align: center;
            padding: 3rem 1rem;
            color: #8B7355;
        }

        .empty-state-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .filter-group {
            display: flex;
            gap: 0.5rem;
            margin-bottom: 1.5rem;
            flex-wrap: wrap;
        }

        .filter-btn {
            padding: 0.5rem 1rem;
            background: rgba(255, 255, 255, 0.7);
            border: 2px solid #E8DCC8;
            border-radius: 8px;
            font-family: 'Crimson Pro', serif;
            font-size: 0.95rem;
            color: #8B7355;
            cursor: pointer;
            transition: all 0.3s;
        }

        .filter-btn:hover {
            border-color: #C9A87C;
        }

        .filter-btn.active {
            background: #C9A87C;
            color: white;
            border-color: #C9A87C;
        }

        @media (max-width: 640px) {
            h1 {
                font-size: 2rem;
            }

            .task-input-group {
                flex-direction: column;
            }

            .dashboard {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>✨ Checklist của tôi</h1>
            <p class="subtitle">Ghi chú nhỏ cho những việc cần làm</p>
        </header>

        <div class="tabs">
            <button class="tab active" onclick="switchTab('dashboard')">📊 Tổng quan</button>
            <button class="tab" onclick="switchTab('today')">☀️ Hôm nay</button>
            <button class="tab" onclick="switchTab('week')">📅 Tuần này</button>
            <button class="tab" onclick="switchTab('month')">🗓️ Tháng này</button>
        </div>

        <!-- Dashboard Tab -->
        <div id="dashboard" class="tab-content active">
            <div class="dashboard">
                <div class="stat-card">
                    <div class="stat-number" id="totalTasks">0</div>
                    <div class="stat-label">Tổng số việc</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number" id="completedTasks">0</div>
                    <div class="stat-label">Đã hoàn thành</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number" id="pendingTasks">0</div>
                    <div class="stat-label">Chưa làm</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number" id="progressPercent">0%</div>
                    <div class="stat-label">Tiến độ</div>
                </div>
            </div>

            <div class="filter-group">
                <button class="filter-btn active" onclick="filterDashboard('all')">Tất cả</button>
                <button class="filter-btn" onclick="filterDashboard('completed')">Đã hoàn thành</button>
                <button class="filter-btn" onclick="filterDashboard('pending')">Chưa làm</button>
            </div>

            <div id="dashboardTasks" class="task-list"></div>
        </div>

        <!-- Today Tab -->
        <div id="today" class="tab-content">
            <div class="add-task-container">
                <div class="task-input-group">
                    <input type="text" id="todayInput" placeholder="Thêm việc cần làm hôm nay..." onkeypress="handleEnter(event, 'today')">
                    <button class="btn" onclick="addTask('today')">Thêm +</button>
                </div>
            </div>
            <div id="todayTasks" class="task-list"></div>
        </div>

        <!-- Week Tab -->
        <div id="week" class="tab-content">
            <div class="add-task-container">
                <div class="task-input-group">
                    <input type="text" id="weekInput" placeholder="Thêm việc cần làm tuần này..." onkeypress="handleEnter(event, 'week')">
                    <button class="btn" onclick="addTask('week')">Thêm +</button>
                </div>
            </div>
            <div id="weekTasks" class="task-list"></div>
        </div>

        <!-- Month Tab -->
        <div id="month" class="tab-content">
            <div class="add-task-container">
                <div class="task-input-group">
                    <input type="text" id="monthInput" placeholder="Thêm việc cần làm tháng này..." onkeypress="handleEnter(event, 'month')">
                    <button class="btn" onclick="addTask('month')">Thêm +</button>
                </div>
            </div>
            <div id="monthTasks" class="task-list"></div>
        </div>
    </div>

    <script>
        let tasks = {
            today: [],
            week: [],
            month: []
        };

        let currentDashboardFilter = 'all';

        function loadTasks() {
            const saved = localStorage.getItem('checklistTasks');
            if (saved) {
                tasks = JSON.parse(saved);
            }
            renderAll();
        }

        function saveTasks() {
            localStorage.setItem('checklistTasks', JSON.stringify(tasks));
        }

        function addTask(period) {
            const input = document.getElementById(period + 'Input');
            const text = input.value.trim();
            
            if (text === '') return;

            tasks[period].push({
                id: Date.now(),
                text: text,
                completed: false,
                createdAt: new Date().toISOString()
            });

            input.value = '';
            saveTasks();
            renderAll();
        }

        function handleEnter(event, period) {
            if (event.key === 'Enter') {
                addTask(period);
            }
        }

        function toggleTask(period, id) {
            const task = tasks[period].find(t => t.id === id);
            if (task) {
                task.completed = !task.completed;
                saveTasks();
                renderAll();
            }
        }

        function deleteTask(period, id) {
            tasks[period] = tasks[period].filter(t => t.id !== id);
            saveTasks();
            renderAll();
        }

        function renderTasks(period) {
            const container = document.getElementById(period + 'Tasks');
            const taskList = tasks[period];

            if (taskList.length === 0) {
                container.innerHTML = `
                    <div class="empty-state">
                        <div class="empty-state-icon">🌸</div>
                        <p>Chưa có việc nào cần làm</p>
                    </div>
                `;
                return;
            }

            container.innerHTML = taskList.map(task => `
                <div class="task-item ${task.completed ? 'completed' : ''}">
                    <div class="checkbox ${task.completed ? 'checked' : ''}" 
                         onclick="toggleTask('${period}', ${task.id})">
                    </div>
                    <div class="task-text">${task.text}</div>
                    <button class="delete-btn" onclick="deleteTask('${period}', ${task.id})">×</button>
                </div>
            `).join('');
        }

        function updateStats() {
            const allTasks = [...tasks.today, ...tasks.week, ...tasks.month];
            const total = allTasks.length;
            const completed = allTasks.filter(t => t.completed).length;
            const pending = total - completed;
            const progress = total > 0 ? Math.round((completed / total) * 100) : 0;

            document.getElementById('totalTasks').textContent = total;
            document.getElementById('completedTasks').textContent = completed;
            document.getElementById('pendingTasks').textContent = pending;
            document.getElementById('progressPercent').textContent = progress + '%';
        }

        function renderDashboard() {
            const container = document.getElementById('dashboardTasks');
            let allTasks = [
                ...tasks.today.map(t => ({...t, period: 'today', periodLabel: '☀️ Hôm nay'})),
                ...tasks.week.map(t => ({...t, period: 'week', periodLabel: '📅 Tuần này'})),
                ...tasks.month.map(t => ({...t, period: 'month', periodLabel: '🗓️ Tháng này'}))
            ];

            if (currentDashboardFilter === 'completed') {
                allTasks = allTasks.filter(t => t.completed);
            } else if (currentDashboardFilter === 'pending') {
                allTasks = allTasks.filter(t => !t.completed);
            }

            if (allTasks.length === 0) {
                container.innerHTML = `
                    <div class="empty-state">
                        <div class="empty-state-icon">🌸</div>
                        <p>Không có việc nào</p>
                    </div>
                `;
                return;
            }

            container.innerHTML = allTasks.map(task => `
                <div class="task-item ${task.completed ? 'completed' : ''}">
                    <div class="checkbox ${task.completed ? 'checked' : ''}" 
                         onclick="toggleTask('${task.period}', ${task.id})">
                    </div>
                    <div class="task-text">
                        <span style="font-size: 0.85rem; color: #C9A87C; margin-right: 0.5rem;">${task.periodLabel}</span>
                        ${task.text}
                    </div>
                    <button class="delete-btn" onclick="deleteTask('${task.period}', ${task.id})">×</button>
                </div>
            `).join('');
        }

        function filterDashboard(filter) {
            currentDashboardFilter = filter;
            
            document.querySelectorAll('.filter-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            event.target.classList.add('active');
            
            renderDashboard();
        }

        function renderAll() {
            renderTasks('today');
            renderTasks('week');
            renderTasks('month');
            updateStats();
            renderDashboard();
        }

        function switchTab(tabName) {
            document.querySelectorAll('.tab').forEach(tab => {
                tab.classList.remove('active');
            });
            document.querySelectorAll('.tab-content').forEach(content => {
                content.classList.remove('active');
            });

            event.target.classList.add('active');
            document.getElementById(tabName).classList.add('active');
        }

        loadTasks();
    </script>
</body>
</html>
