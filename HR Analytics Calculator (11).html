<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HR Analytics Calculator</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        .calculator {
            border: 1px solid #ccc;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 400px;
        }
        .calculator h2 {
            text-align: center;
            color: #007BFF;
        }
        .calculator input, .calculator select {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }
        .calculator button {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: none;
            border-radius: 5px;
            background-color: #007BFF;
            color: #fff;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .calculator button:hover {
            background-color: #0056b3;
        }
        .result {
            margin-top: 20px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #e9e9e9;
        }
        .language-buttons {
            display: flex;
            justify-content: space-around;
            margin-bottom: 20px;
        }
        .language-buttons button {
            width: 45%;
            padding: 10px;
            border: none;
            border-radius: 5px;
            background-color: #007BFF;
            color: #fff;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .language-buttons button:hover {
            background-color: #0056b3;
        }
        .currency-selector {
            margin-bottom: 20px;
        }
        .footer {
            text-align: center;
            margin-top: 20px;
            font-size: 14px;
            color: #555;
        }
        @media (max-width: 768px) {
            .calculator {
                padding: 15px;
            }
            .calculator h2 {
                font-size: 1.5em;
            }
            .calculator input, .calculator select {
                padding: 8px;
                font-size: 14px;
            }
            .calculator button {
                padding: 8px;
                font-size: 14px;
            }
            .language-buttons button {
                padding: 8px;
                font-size: 14px;
            }
            .footer {
                font-size: 12px;
            }
        }
        @media (max-width: 480px) {
            .calculator {
                padding: 10px;
            }
            .calculator h2 {
                font-size: 1.2em;
            }
            .calculator input, .calculator select {
                padding: 6px;
                font-size: 12px;
            }
            .calculator button {
                padding: 6px;
                font-size: 12px;
            }
            .language-buttons button {
                padding: 6px;
                font-size: 12px;
            }
            .footer {
                font-size: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="calculator">
        <div class="language-buttons">
            <button onclick="toggleLanguage('en')">English</button>
            <button onclick="toggleLanguage('ar')">العربية</button>
        </div>
        <div class="currency-selector">
            <label for="currency">Select Currency:</label>
            <select id="currency" onchange="updateCurrency()">
                <option value="USD">USD (\$)</option>
                <option value="EUR">EUR (€)</option>
                <option value="GBP">GBP (£)</option>
                <option value="AED">AED (د.إ)</option>
                <option value="SAR">SAR (﷼)</option>
                <option value="EGP">EGP (ج.م)</option>
                <!-- Add more currencies as needed -->
            </select>
        </div>
        <h2 id="title">HR Analytics Calculator</h2>
        <select id="metric">
            <option value="timeToHire">Time to Hire</option>
            <option value="costPerHire">Cost per Hire</option>
            <option value="offerAcceptanceRate">Offer Acceptance Rate</option>
            <option value="trainingROI">Training ROI</option>
            <option value="compaRatio">Compa Ratio</option>
            <option value="voluntaryTurnoverRate">Voluntary Turnover Rate</option>
            <option value="trainingExpensesPerEmployee">Training Expenses per Employee</option>
            <option value="employeeAbsenteeismRates">Employee Absenteeism Rates</option>
            <option value="internalTransferPromotionRates">Internal Transfer and Promotion Rates</option>
            <option value="revenuePerEmployee">Revenue per Employee</option>
            <option value="injuriesRate">Injuries Rate</option>
            <option value="trainingHoursPerEmployee">Training Hours per Employee</option>
            <option value="costOfTurnover">Cost of Turnover</option>
            <option value="humanCapitalROI">Human Capital ROI</option>
            <option value="nonComplianceRate">Non-compliance Rate</option>
        </select>
        <div id="inputs">
            <!-- Inputs will be dynamically generated here -->
        </div>
        <button onclick="calculate()">Calculate</button>
        <div class="result" id="result"></div>
    </div>
    <div class="footer">
        Created by: Ramy Ibrahim, SPHRi, PAC
    </div>

    <script>
        const metrics = {
            timeToHire: {
                inputs: [
                    { label: "Date of Receiving the Order", id: "startDate", type: "date" },
                    { label: "Date of Completion of the Request", id: "endDate", type: "date" },
                    { label: "Number of Hires", id: "numberOfHires", type: "number" }
                ],
                calculate: (startDate, endDate, numberOfHires) => {
                    const start = new Date(startDate);
                    const end = new Date(endDate);
                    const diffTime = Math.abs(end - start);
                    const diffDays = Math.ceil(diffTime / (1000 * 60 * 60 * 24));
                    return diffDays / numberOfHires;
                },
                description: {
                    en: "Time to Hire is the average number of days it takes to fill a position.",
                    ar: "وقت التعيين هو متوسط عدد الأيام التي يستغرقها ملء منصب."
                },
                computation: {
                    en: "(Date of Completion of the Request - Date of Receiving the Order) / Number of Hires",
                    ar: "(تاريخ إتمام الطلب - تاريخ استلام الطلب) / عدد الموظفين الجدد"
                }
            },
            costPerHire: {
                inputs: [
                    { label: "Total Recruitment Costs", id: "totalCosts", type: "number", currency: true },
                    { label: "Number of Hires", id: "numberOfHires", type: "number" }
                ],
                calculate: (totalCosts, numberOfHires) => totalCosts / numberOfHires,
                description: {
                    en: "Cost per Hire is the total cost spent on recruitment divided by the number of hires.",
                    ar: "تكلفة التعيين هي إجمالي المبلغ المنفق على التوظيف مقسومًا على عدد الموظفين الجدد."
                },
                computation: {
                    en: "Total Recruitment Costs / Number of Hires",
                    ar: "إجمالي تكاليف التوظيف / عدد الموظفين الجدد"
                }
            },
            offerAcceptanceRate: {
                inputs: [
                    { label: "Number of Offers Accepted", id: "offersAccepted", type: "number" },
                    { label: "Total Number of Offers", id: "totalOffers", type: "number" }
                ],
                calculate: (offersAccepted, totalOffers) => (offersAccepted / totalOffers) * 100,
                description: {
                    en: "Offer Acceptance Rate is the percentage of job offers accepted by candidates.",
                    ar: "معدل قبول العروض هو النسبة المئوية للعروض الوظيفية التي تم قبولها من قبل المرشحين."
                },
                computation: {
                    en: "(Number of Offers Accepted / Total Number of Offers) * 100",
                    ar: "(عدد العروض المقبولة / إجمالي عدد العروض) * 100"
                }
            },
            trainingROI: {
                inputs: [
                    { label: "Benefits from Training", id: "benefits", type: "number", currency: true },
                    { label: "Cost of Training", id: "trainingCost", type: "number", currency: true }
                ],
                calculate: (benefits, trainingCost) => ((benefits - trainingCost) / trainingCost) * 100,
                description: {
                    en: "Training ROI is the return on investment from training programs.",
                    ar: "عائد الاستثمار في التدريب هو العائد على الاستثمار من برامج التدريب."
                },
                computation: {
                    en: "((Benefits from Training - Cost of Training) / Cost of Training) * 100",
                    ar: "((فوائد التدريب - تكلفة التدريب) / تكلفة التدريب) * 100"
                }
            },
            compaRatio: {
                inputs: [
                    { label: "Employee Salary", id: "employeeSalary", type: "number", currency: true },
                    { label: "Market Salary", id: "marketSalary", type: "number", currency: true }
                ],
                calculate: (employeeSalary, marketSalary) => (employeeSalary / marketSalary) * 100,
                description: {
                    en: "Compa Ratio is the ratio of an employee's salary to the market salary for a similar position.",
                    ar: "نسبة المقارنة هي نسبة راتب الموظف إلى راتب السوق لمنصب مماثل."
                },
                computation: {
                    en: "(Employee Salary / Market Salary) * 100",
                    ar: "(راتب الموظف / راتب السوق) * 100"
                }
            },
            voluntaryTurnoverRate: {
                inputs: [
                    { label: "Number of Voluntary Separations", id: "voluntarySeparations", type: "number" },
                    { label: "Average Number of Employees", id: "averageEmployees", type: "number" }
                ],
                calculate: (voluntarySeparations, averageEmployees) => (voluntarySeparations / averageEmployees) * 100,
                description: {
                    en: "Voluntary Turnover Rate is the percentage of employees who leave the organization voluntarily.",
                    ar: "معدل الدوران الطوعي هو النسبة المئوية للموظفين الذين يغادرون المنظمة طواعية."
                },
                computation: {
                    en: "(Number of Voluntary Separations / Average Number of Employees) * 100",
                    ar: "(عدد الانفصالات الطوعية / متوسط عدد الموظفين) * 100"
                }
            },
            trainingExpensesPerEmployee: {
                inputs: [
                    { label: "Total Training Expenses", id: "totalTrainingExpenses", type: "number", currency: true },
                    { label: "Number of Employees", id: "numberOfEmployees", type: "number" }
                ],
                calculate: (totalTrainingExpenses, numberOfEmployees) => totalTrainingExpenses / numberOfEmployees,
                description: {
                    en: "Training Expenses per Employee is the total training expenses divided by the number of employees.",
                    ar: "تكاليف التدريب لكل موظف هي إجمالي تكاليف التدريب مقسومًا على عدد الموظفين."
                },
                computation: {
                    en: "Total Training Expenses / Number of Employees",
                    ar: "إجمالي تكاليف التدريب / عدد الموظفين"
                }
            },
            employeeAbsenteeismRates: {
                inputs: [
                    { label: "Number of Absent Days", id: "absentDays", type: "number" },
                    { label: "Number of Employees", id: "numberOfEmployees", type: "number" },
                    { label: "Working Days during the Period", id: "workingDays", type: "number" }
                ],
                calculate: (absentDays, numberOfEmployees, workingDays) => {
                    const totalPossibleWorkDays = numberOfEmployees * workingDays;
                    return (absentDays / totalPossibleWorkDays) * 100;
                },
                description: {
                    en: "Employee Absenteeism Rates is the percentage of days employees are absent from work.",
                    ar: "معدل غياب الموظفين هو النسبة المئوية للأيام التي يغيب فيها الموظفون عن العمل."
                },
                computation: {
                    en: "(Number of Absent Days / (Number of Employees * Working Days during the Period)) * 100",
                    ar: "(عدد أيام الغياب / (عدد الموظفين * أيام العمل خلال الفترة)) * 100"
                }
            },
            internalTransferPromotionRates: {
                inputs: [
                    { label: "Number of Internal Transfers and Promotions", id: "internalTransfersPromotions", type: "number" },
                    { label: "Number of Employees", id: "numberOfEmployees", type: "number" }
                ],
                calculate: (internalTransfersPromotions, numberOfEmployees) => (internalTransfersPromotions / numberOfEmployees) * 100,
                description: {
                    en: "Internal Transfer and Promotion Rates is the percentage of employees who have been transferred or promoted internally.",
                    ar: "معدلات التحويل والترقية الداخلية هي النسبة المئوية للموظفين الذين تم نقلهم أو ترقيتهم داخليًا."
                },
                computation: {
                    en: "(Number of Internal Transfers and Promotions / Number of Employees) * 100",
                    ar: "(عدد التحويلات والترقيات الداخلية / عدد الموظفين) * 100"
                }
            },
            revenuePerEmployee: {
                inputs: [
                    { label: "Total Revenue", id: "totalRevenue", type: "number", currency: true },
                    { label: "Number of Employees", id: "numberOfEmployees", type: "number" }
                ],
                calculate: (totalRevenue, numberOfEmployees) => totalRevenue / numberOfEmployees,
                description: {
                    en: "Revenue per Employee is the total revenue divided by the number of employees.",
                    ar: "الإيرادات لكل موظف هي إجمالي الإيرادات مقسومًا على عدد الموظفين."
                },
                computation: {
                    en: "Total Revenue / Number of Employees",
                    ar: "إجمالي الإيرادات / عدد الموظفين"
                }
            },
            injuriesRate: {
                inputs: [
                    { label: "Number of Injuries", id: "numberOfInjuries", type: "number" },
                    { label: "Total Number of Employees", id: "totalEmployees", type: "number" }
                ],
                calculate: (numberOfInjuries, totalEmployees) => (numberOfInjuries / totalEmployees) * 100,
                description: {
                    en: "Injuries Rate is the percentage of employees who have been injured.",
                    ar: "معدل الإصابات هو النسبة المئوية للموظفين الذين تعرضوا للإصابة."
                },
                computation: {
                    en: "(Number of Injuries / Total Number of Employees) * 100",
                    ar: "(عدد الإصابات / إجمالي عدد الموظفين) * 100"
                }
            },
            trainingHoursPerEmployee: {
                inputs: [
                    { label: "Total Training Hours", id: "totalTrainingHours", type: "number" },
                    { label: "Number of Employees Trained", id: "numberOfEmployeesTrained", type: "number" }
                ],
                calculate: (totalTrainingHours, numberOfEmployeesTrained) => totalTrainingHours / numberOfEmployeesTrained,
                description: {
                    en: "Training Hours per Employee is the total training hours divided by the number of employees trained.",
                    ar: "ساعات التدريب لكل موظف هي إجمالي ساعات التدريب مقسومًا على عدد الموظفين الذين تم تدريبهم."
                },
                computation: {
                    en: "Total Training Hours / Number of Employees Trained",
                    ar: "إجمالي ساعات التدريب / عدد الموظفين الذين تم تدريبهم"
                }
            },
            costOfTurnover: {
                inputs: [
                    { label: "Cost of Severances", id: "costOfSeverances", type: "number", currency: true },
                    { label: "Cost of Recruiting", id: "costOfRecruiting", type: "number", currency: true },
                    { label: "Cost of Onboarding", id: "costOfOnboarding", type: "number", currency: true },
                    { label: "Productivity Loss", id: "productivityLoss", type: "number", currency: true }
                ],
                calculate: (costOfSeverances, costOfRecruiting, costOfOnboarding, productivityLoss) =>
                    parseFloat(costOfSeverances) + parseFloat(costOfRecruiting) + parseFloat(costOfOnboarding) + parseFloat(productivityLoss),
                description: {
                    en: "Cost of Turnover is the total cost of severances, recruiting, onboarding, and productivity loss.",
                    ar: "تكلفة الدوران هي التكلفة الإجمالية للتعويضات والتوظيف والتوظيف وفقدان الإنتاجية."
                },
                computation: {
                    en: "Cost of Severances + Cost of Recruiting + Cost of Onboarding + Productivity Loss",
                    ar: "تكلفة التعويضات + تكلفة التوظيف + تكلفة التوظيف + فقدان الإنتاجية"
                }
            },
            humanCapitalROI: {
                inputs: [
                    { label: "Revenue", id: "revenue", type: "number", currency: true },
                    { label: "Operating Expenses", id: "operatingExpenses", type: "number", currency: true },
                    { label: "Employee Costs", id: "employeeCosts", type: "number", currency: true }
                ],
                calculate: (revenue, operatingExpenses, employeeCosts) =>
                    ((revenue - (operatingExpenses - employeeCosts)) / employeeCosts) * 100,
                description: {
                    en: "Human Capital ROI is the financial return on the investment in employees. It shows how effectively an organization generates revenue from its workforce relative to the cost of their compensation and benefits.",
                    ar: "عائد رأس المال البشري هو العائد المالي على الاستثمار في الموظفين. يظهر كيف تتمكن المنظمة من توليد الإيرادات من قوتها العاملة بالنسبة إلى تكاليف تعويضاتهم ومزاياهم."
                },
                computation: {
                    en: "((Revenue - (Operating Expenses - Employee Costs)) / Employee Costs) * 100",
                    ar: "((الإيرادات - (المصاريف التشغيلية - تكاليف الموظفين)) / تكاليف الموظفين) * 100"
                }
            },
            nonComplianceRate: {
                inputs: [
                    { label: "Number of Employees suspended or got warning", id: "numberOfEmployeesSuspendedOrWarned", type: "number" },
                    { label: "Total Number of Employees", id: "totalEmployees", type: "number" }
                ],
                calculate: (numberOfEmployeesSuspendedOrWarned, totalEmployees) =>
                    (numberOfEmployeesSuspendedOrWarned / totalEmployees) * 100,
                description: {
                    en: "Non-compliance Rate is the percentage of employees failing to adhere to established policies, procedures, or regulations.",
                    ar: "معدل عدم الالتزام هو النسبة المئوية للموظفين الذين يفشلون في الالتزام بالسياسات والإجراءات أو اللوائح المعمول بها."
                },
                computation: {
                    en: "(Number of Employees suspended or got warning / Total Number of Employees) * 100",
                    ar: "(عدد الموظفين المعلقين أو تلقوا التحذير / إجمالي عدد الموظفين) * 100"
                }
            }
        };

        let currentCurrency = 'USD';
        let currentLanguage = 'en';

        function updateCurrency() {
            currentCurrency = document.getElementById('currency').value;
            generateInputs(document.getElementById('metric').value);
        }

        function generateInputs(metric) {
            const inputsDiv = document.getElementById('inputs');
            inputsDiv.innerHTML = '';
            metrics[metric].inputs.forEach(input => {
                const label = document.createElement('label');
                label.innerText = input.label;
                const inputField = document.createElement('input');
                inputField.type = input.type;
                inputField.id = input.id;
                if (input.currency) {
                    inputField.placeholder = `e.g., 1000 ${getCurrencySymbol(currentCurrency)}`;
                    inputField.addEventListener('input', function() {
                        this.value = this.value.replace(/[^0-9.]/g, '');
                    });
                }
                inputsDiv.appendChild(label);
                inputsDiv.appendChild(inputField);
            });
        }

        function getCurrencySymbol(currency) {
            const symbols = {
                USD: '\$',
                EUR: '€',
                GBP: '£',
                AED: 'د.إ',
                SAR: '﷼',
                EGP: 'ج.م'
                // Add more currency symbols as needed
            };
            return symbols[currency] || '';
        }

        function calculate() {
            const metric = document.getElementById('metric').value;
            const inputs = metrics[metric].inputs.map(input => document.getElementById(input.id).value);
            const result = metrics[metric].calculate(...inputs);
            const description = metrics[metric].description[currentLanguage];
            const computation = metrics[metric].computation[currentLanguage];
            const resultSuffix = metric === 'timeToHire' ? 'Days' : (metric === 'compaRatio' || metric === 'trainingROI' ? '%' : (metrics[metric].inputs.some(input => input.currency) ? getCurrencySymbol(currentCurrency) : (metric === 'trainingHoursPerEmployee' ? 'Hours' : '%')));
            document.getElementById('result').innerHTML = `
                <strong>Result:</strong> ${result.toFixed(2)}${resultSuffix}<br>
                <strong>Description:</strong> ${description}<br>
                <strong>Computation:</strong> ${computation}
            `;
        }

        document.getElementById('metric').addEventListener('change', function() {
            const metric = this.value;
            generateInputs(metric);
        });

        document.getElementById('metric').dispatchEvent(new Event('change'));

        // Language toggle
        function toggleLanguage(lang) {
            currentLanguage = lang;
            const titles = {
                en: "HR Analytics Calculator",
                ar: "حاسبة تحليلات الموارد البشرية"
            };
            const metricLabels = {
                en: {
                    timeToHire: "Time to Hire",
                    costPerHire: "Cost per Hire",
                    offerAcceptanceRate: "Offer Acceptance Rate",
                    trainingROI: "Training ROI",
                    compaRatio: "Compa Ratio",
                    voluntaryTurnoverRate: "Voluntary دوران Rate",
                    trainingExpensesPerEmployee: "Training Expenses per Employee",
                    employeeAbsenteeismRates: "Employee Absenteeism Rates",
                    internalTransferPromotionRates: "Internal Transfer and Promotion Rates",
                    revenuePerEmployee: "Revenue per Employee",
                    injuriesRate: "Injuries Rate",
                    trainingHoursPerEmployee: "Training Hours per Employee",
                    costOfTurnover: "Cost of دوران",
                    humanCapitalROI: "Human Capital ROI",
                    nonComplianceRate: "Non-compliance Rate"
                },
                ar: {
                    timeToHire: "وقت التعيين",
                    costPerHire: "تكلفة التعيين",
                    offerAcceptanceRate: "معدل قبول العروض",
                    trainingROI: "عائد الاستثمار في التدريب",
                    compaRatio: "نسبة المقارنة",
                    voluntaryTurnoverRate: "معدل الدوران الطوعي",
                    trainingExpensesPerEmployee: "تكاليف التدريب لكل موظف",
                    employeeAbsenteeismRates: "معدل غياب الموظفين",
                    internalTransferPromotionRates: "معدلات التحويل والترقية الداخلية",
                    revenuePerEmployee: "الإيرادات لكل موظف",
                    injuriesRate: "معدل الإصابات",
                    trainingHoursPerEmployee: "ساعات التدريب لكل موظف",
                    costOfTurnover: "تكلفة الدوران",
                    humanCapitalROI: "عائد رأس المال البشري",
                    nonComplianceRate: "معدل عدم الالتزام"
                }
            };
            const labels = {
                en: {
                    startDate: "Date of Receiving the Order",
                    endDate: "Date of Completion of the Request",
                    totalCosts: "Total Recruitment Costs",
                    numberOfHires: "Number of Hires",
                    offersAccepted: "Number of Offers Accepted",
                    totalOffers: "Total Number of Offers",
                    benefits: "Benefits from Training",
                    trainingCost: "Cost of Training",
                    employeeSalary: "Employee Salary",
                    marketSalary: "Market Salary",
                    voluntarySeparations: "Number of Voluntary Separations",
                    averageEmployees: "Average Number of Employees",
                    totalTrainingExpenses: "Total Training Expenses",
                    numberOfEmployees: "Number of Employees",
                    internalTransfersPromotions: "Number of Internal Transfers and Promotions",
                    totalEmployees: "Total Number of Employees",
                    totalRevenue: "Total Revenue",
                    numberOfInjuries: "Number of Injuries",
                    totalTrainingHours: "Total Training Hours",
                    numberOfEmployeesTrained: "Number of Employees Trained",
                    costOfSeverances: "Cost of Severances",
                    costOfRecruiting: "Cost of Recruiting",
                    costOfOnboarding: "Cost of Onboarding",
                    productivityLoss: "Productivity Loss",
                    revenue: "Revenue",
                    operatingExpenses: "Operating Expenses",
                    employeeCosts: "Employee Costs",
                    numberOfEmployeesSuspendedOrWarned: "Number of Employees suspended or got warning"
                },
                ar: {
                    startDate: "تاريخ استلام الطلب",
                    endDate: "تاريخ إتمام الطلب",
                    totalCosts: "إجمالي تكاليف التوظيف",
                    numberOfHires: "عدد الموظفين الجدد",
                    offersAccepted: "عدد العروض المقبولة",
                    totalOffers: "إجمالي عدد العروض",
                    benefits: "فوائد التدريب",
                    trainingCost: "تكلفة التدريب",
                    employeeSalary: "راتب الموظف",
                    marketSalary: "راتب السوق",
                    voluntarySeparations: "عدد الانفصالات الطوعية",
                    averageEmployees: "متوسط عدد الموظفين",
                    totalTrainingExpenses: "إجمالي تكاليف التدريب",
                    numberOfEmployees: "عدد الموظفين",
                    internalTransfersPromotions: "عدد التحويلات والترقيات الداخلية",
                    totalEmployees: "إجمالي عدد الموظفين",
                    totalRevenue: "إجمالي الإيرادات",
                    numberOfInjuries: "عدد الإصابات",
                    totalTrainingHours: "إجمالي ساعات التدريب",
                    numberOfEmployeesTrained: "عدد الموظفين الذين تم تدريبهم",
                    costOfSeverances: "تكلفة التعويضات",
                    costOfRecruiting: "تكلفة التوظيف",
                    costOfOnboarding: "تكلفة التوظيف",
                    productivityLoss: "فقدان الإنتاجية",
                    revenue: "الإيرادات",
                    operatingExpenses: "المصاريف التشغيلية",
                    employeeCosts: "تكاليف الموظفين",
                    numberOfEmployeesSuspendedOrWarned: "عدد الموظفين المعلقين أو تلقوا التحذير"
                }
            };
            document.getElementById('title').innerText = titles[lang];
            const metricSelect = document.getElementById('metric');
            metricSelect.innerHTML = '';
            for (const key in metricLabels[lang]) {
                const option = document.createElement('option');
                option.value = key;
                option.innerText = metricLabels[lang][key];
                metricSelect.appendChild(option);
            }
            metrics[metricSelect.value].inputs.forEach(input => {
                document.querySelector(`label[for=${input.id}]`).innerText = labels[lang][input.id];
            });
        }

        // Example usage: toggleLanguage('ar');
    </script>
</body>
</html>
