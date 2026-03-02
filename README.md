<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SupportTicketRouter — Mastery in API Wrapper Composition for AI Red Teaming</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&amp;family=Space+Grotesk:wght@500;600&amp;display=swap');
        
        :root {
            --primary: #3b82f6;
        }
        
        body {
            font-family: 'Inter', system_ui, sans-serif;
        }
        
        .title-font {
            font-family: 'Space Grotesk', sans-serif;
        }

        .code-header {
            background: #18181b;
            color: #a1a1aa;
            font-family: ui-monospace, monospace;
        }

        pre {
            font-size: 0.875rem;
            line-height: 1.5;
        }

        .print-break {
            break-after: page;
        }

        @media print {
            body { 
                font-size: 11pt; 
                line-height: 1.4;
            }
            .no-print { display: none !important; }
            pre, code { 
                font-size: 9.5pt !important;
                background: #f8fafc !important;
                color: #111827 !important;
                padding: 1rem !important;
                border: 1px solid #e5e7eb !important;
            }
            .code-header {
                background: #f1f5f9 !important;
                color: #64748b !important;
            }
            table { page-break-inside: auto; }
            tr { page-break-inside: avoid; page-break-after: auto; }
            h1, h2, h3 { break-after: avoid; }
        }
        
        .tail-container {
            max-width: 980px;
            margin: 0 auto;
        }
    </style>
</head>
<body class="bg-zinc-50 text-zinc-900">
    <div class="tail-container py-12 px-6">
        
        <!-- HEADER -->
        <div class="mb-16 border-b border-zinc-200 pb-12">
            <div class="flex items-center gap-x-4 mb-6">
                <div class="w-14 h-14 bg-blue-600 text-white rounded-2xl flex items-center justify-center text-3xl shadow-inner">
                    <i class="fa-solid fa-route"></i>
                </div>
                <div>
                    <h1 class="title-font text-5xl font-semibold tracking-tighter text-zinc-900">SupportTicketRouter</h1>
                    <p class="text-blue-600 font-medium text-xl">Master API Wrapper Composition</p>
                </div>
            </div>
            <p class="max-w-2xl text-xl text-zinc-600 leading-relaxed">
                Your hands-on training ground for mastering API wrapper composition — a foundational skill for AI red teaming.
            </p>
            <div class="mt-8 flex flex-wrap gap-4 text-sm">
                <div class="bg-white shadow-sm border border-zinc-200 rounded-2xl px-5 py-3 flex items-center gap-x-3">
                    <i class="fa-solid fa-check text-emerald-500"></i>
                    <span class="font-medium">Level 1–3 Complete</span>
                </div>
                <div class="bg-white shadow-sm border border-zinc-200 rounded-2xl px-5 py-3 flex items-center gap-x-3">
                    <span class="font-mono text-rose-500">GPT-4o-mini</span>
                    <span class="text-zinc-400">→</span>
                    <span class="font-mono text-violet-500">Stripe</span>
                    <span class="text-zinc-400">→</span>
                    <span class="font-mono text-amber-500">Slack</span>
                </div>
            </div>
        </div>

        <!-- WHAT THIS PROJECT TEACHES -->
        <div class="mb-16">
            <h2 class="text-3xl font-semibold mb-6 flex items-center gap-x-3">
                <span class="text-blue-600">What This Project Teaches</span>
            </h2>
            <div class="bg-white rounded-3xl shadow-sm border border-zinc-100 overflow-hidden">
                <table class="w-full">
                    <thead class="bg-zinc-100">
                        <tr>
                            <th class="px-8 py-5 text-left font-medium text-zinc-500">Skill</th>
                            <th class="px-8 py-5 text-left font-medium text-zinc-500">Why It Matters for AI Red Teaming</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-zinc-100">
                        <tr>
                            <td class="px-8 py-6 font-medium">Wrapper chaining</td>
                            <td class="px-8 py-6 text-zinc-600">Red team tools chain 5-10+ APIs (Ollama → Slack → Gmail → Stripe)</td>
                        </tr>
                        <tr>
                            <td class="px-8 py-6 font-medium">Domain modeling</td>
                            <td class="px-8 py-6 text-zinc-600">Convert messy API responses to clean objects for analysis</td>
                        </tr>
                        <tr>
                            <td class="px-8 py-6 font-medium">Facade pattern</td>
                            <td class="px-8 py-6 text-zinc-600">Hide complexity behind clean interfaces (critical for agent security)</td>
                        </tr>
                        <tr>
                            <td class="px-8 py-6 font-medium">Error resilience</td>
                            <td class="px-8 py-6 text-zinc-600">APIs fail; red team tools must survive</td>
                        </tr>
                        <tr>
                            <td class="px-8 py-6 font-medium">Configuration management</td>
                            <td class="px-8 py-6 text-zinc-600">API keys, secrets, sandbox vs production</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>

        <!-- 6-LEVEL PROGRESSION -->
        <div class="mb-16 print-break">
            <h2 class="text-3xl font-semibold mb-6">The 6-Level Progression This Project Covers</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <div class="bg-emerald-50 border border-emerald-200 rounded-3xl p-6 flex items-start gap-x-4">
                    <div class="w-8 h-8 bg-emerald-600 text-white rounded-2xl flex items-center justify-center font-bold flex-shrink-0">1</div>
                    <div>
                        <span class="text-emerald-700 font-medium">Level 1:</span>
                        <span class="text-emerald-600"> ✅ You already have (OpenAI wrapper provided)</span>
                    </div>
                </div>
                <div class="bg-emerald-50 border border-emerald-200 rounded-3xl p-6 flex items-start gap-x-4">
                    <div class="w-8 h-8 bg-emerald-600 text-white rounded-2xl flex items-center justify-center font-bold flex-shrink-0">2</div>
                    <div>
                        <span class="text-emerald-700 font-medium">Level 2:</span>
                        <span class="text-emerald-600"> ✅ Chain OpenAI → Stripe → Slack</span>
                    </div>
                </div>
                <div class="bg-emerald-50 border border-emerald-200 rounded-3xl p-6 flex items-start gap-x-4">
                    <div class="w-8 h-8 bg-emerald-600 text-white rounded-2xl flex items-center justify-center font-bold flex-shrink-0">3</div>
                    <div>
                        <span class="text-emerald-700 font-medium">Level 3:</span>
                        <span class="text-emerald-600"> ✅ Facade hides all three</span>
                    </div>
                </div>
                <div class="bg-amber-50 border border-amber-200 rounded-3xl p-6 flex items-start gap-x-4">
                    <div class="w-8 h-8 bg-amber-500 text-white rounded-2xl flex items-center justify-center font-bold flex-shrink-0">4</div>
                    <div class="text-amber-700">Add retries, circuit breakers</div>
                </div>
                <div class="bg-amber-50 border border-amber-200 rounded-3xl p-6 flex items-start gap-x-4">
                    <div class="w-8 h-8 bg-amber-500 text-white rounded-2xl flex items-center justify-center font-bold flex-shrink-0">5</div>
                    <div class="text-amber-700">Make swappable (OpenAI ↔ Anthropic)</div>
                </div>
                <div class="bg-amber-50 border border-amber-200 rounded-3xl p-6 flex items-start gap-x-4">
                    <div class="w-8 h-8 bg-amber-500 text-white rounded-2xl flex items-center justify-center font-bold flex-shrink-0">6</div>
                    <div class="text-amber-700">AI agent orchestration</div>
                </div>
            </div>
        </div>

        <!-- STEP-BY-STEP IMPLEMENTATION -->
        <div class="mb-20">
            <h2 class="text-3xl font-semibold mb-8">Step-by-Step Implementation</h2>
            
            <div class="space-y-14">
                
                <!-- Step 1 -->
                <div>
                    <div class="flex items-center gap-x-4 mb-4">
                        <div class="bg-blue-100 text-blue-700 w-8 h-8 rounded-2xl flex items-center justify-center font-bold">1</div>
                        <h3 class="text-2xl font-semibold">Create Project Structure</h3>
                    </div>
                    <pre class="bg-zinc-950 text-zinc-300 p-8 rounded-3xl overflow-auto"><code class="text-sm">mkdir support_ticket_router &amp;&amp; cd support_ticket_router
mkdir wrappers
touch wrappers/__init__.py</code></pre>
                </div>

                <!-- Step 2 -->
                <div>
                    <div class="flex items-center gap-x-4 mb-4">
                        <div class="bg-blue-100 text-blue-700 w-8 h-8 rounded-2xl flex items-center justify-center font-bold">2</div>
                        <h3 class="text-2xl font-semibold">Install Dependencies</h3>
                    </div>
                    <pre class="bg-zinc-950 text-zinc-300 p-8 rounded-3xl overflow-auto"><code class="text-sm">pip install openai&gt;=1.60.0 stripe&gt;=10.0.0 slack-sdk&gt;=3.30.0 \
    python-dotenv&gt;=1.0.0 pydantic&gt;=2.10.0 typer&gt;=0.15.0</code></pre>
                </div>

                <!-- Step 3: Files -->
                <div>
                    <div class="flex items-center gap-x-4 mb-6">
                        <div class="bg-blue-100 text-blue-700 w-8 h-8 rounded-2xl flex items-center justify-center font-bold">3</div>
                        <h3 class="text-2xl font-semibold">Create Files</h3>
                    </div>

                    <!-- .env.example -->
                    <div class="mb-10">
                        <div class="code-header px-6 py-3 rounded-t-3xl flex items-center justify-between text-xs font-medium">
                            <span>.env.example (copy to .env and fill in real keys)</span>
                        </div>
                        <pre class="bg-zinc-950 text-emerald-300 p-8 rounded-b-3xl overflow-auto"><code>OPENAI_API_KEY=sk-...
STRIPE_API_KEY=sk_test_...
SLACK_BOT_TOKEN=xoxb-...
SLACK_CHANNEL=#support-alerts</code></pre>
                    </div>

                    <!-- config.py -->
                    <div class="mb-10">
                        <div class="code-header px-6 py-3 rounded-t-3xl flex items-center justify-between text-xs font-medium">
                            <span>config.py</span>
                        </div>
                        <pre class="bg-zinc-950 text-emerald-300 p-8 rounded-b-3xl overflow-auto"><code>import os
from dotenv import load_dotenv
load_dotenv()

class Config:
    OPENAI_API_KEY = os.getenv("OPENAI_API_KEY")
    STRIPE_API_KEY = os.getenv("STRIPE_API_KEY")
    SLACK_BOT_TOKEN = os.getenv("SLACK_BOT_TOKEN")
    SLACK_CHANNEL = os.getenv("SLACK_CHANNEL", "#support-alerts")

config = Config()</code></pre>
                    </div>

                    <!-- domain.py -->
                    <div class="mb-10">
                        <div class="code-header px-6 py-3 rounded-t-3xl flex items-center justify-between text-xs font-medium">
                            <span>domain.py (your clean data models)</span>
                        </div>
                        <pre class="bg-zinc-950 text-emerald-300 p-8 rounded-b-3xl overflow-auto"><code>from pydantic import BaseModel
from typing import Optional

class IssueAnalysis(BaseModel):
    summary: str
    category: str
    priority: str  # "low" | "medium" | "high"

class CustomerStatus(BaseModel):
    exists: bool
    is_premium: bool = False
    subscription_status: Optional[str] = None</code></pre>
                    </div>

                    <!-- openai_wrapper.py -->
                    <div class="mb-10">
                        <div class="code-header px-6 py-3 rounded-t-3xl flex items-center justify-between text-xs font-medium">
                            <span>wrappers/openai_wrapper.py</span>
                        </div>
                        <pre class="bg-zinc-950 text-emerald-300 p-8 rounded-b-3xl overflow-auto"><code>from openai import OpenAI
from domain import IssueAnalysis

class OpenAIWrapper:
    def __init__(self):
        self.client = OpenAI()

    def analyze_issue(self, issue: str) -&gt; IssueAnalysis:
        response = self.client.chat.completions.create(
            model="gpt-4o-mini",
            messages=[
                {"role": "system", "content": "You are a support classifier. Return JSON only."},
                {"role": "user", "content": f"Analyze this support issue and return JSON with fields: summary, category, priority. Priority must be 'low', 'medium', or 'high'.\n\nIssue: {issue}"}
            ],
            response_format={"type": "json_object"}
        )
        data = response.choices[0].message.content
        return IssueAnalysis.model_validate_json(data)</code></pre>
                    </div>

                    <!-- stripe_wrapper.py -->
                    <div class="mb-10">
                        <div class="code-header px-6 py-3 rounded-t-3xl flex items-center justify-between text-xs font-medium">
                            <span>wrappers/stripe_wrapper.py</span>
                        </div>
                        <pre class="bg-zinc-950 text-emerald-300 p-8 rounded-b-3xl overflow-auto"><code>import stripe
from config import config
from domain import CustomerStatus

class StripeWrapper:
    def __init__(self):
        stripe.api_key = config.STRIPE_API_KEY

    def get_customer_status(self, email: str) -&gt; CustomerStatus:
        try:
            customers = stripe.Customer.list(email=email, limit=1)
            if not customers.data:
                return CustomerStatus(exists=False)
            
            cust = customers.data[0]
            # Check for active subscriptions
            subs = stripe.Subscription.list(customer=cust.id, status="active", limit=1)
            is_premium = len(subs.data) &gt; 0
            
            return CustomerStatus(
                exists=True, 
                is_premium=is_premium,
                subscription_status="active" if is_premium else "inactive"
            )
        except Exception as e:
            print(f"Stripe error: {e}")
            return CustomerStatus(exists=False)</code></pre>
                    </div>

                    <!-- slack_wrapper.py -->
                    <div class="mb-10">
                        <div class="code-header px-6 py-3 rounded-t-3xl flex items-center justify-between text-xs font-medium">
                            <span>wrappers/slack_wrapper.py</span>
                        </div>
                        <pre class="bg-zinc-950 text-emerald-300 p-8 rounded-b-3xl overflow-auto"><code>from slack_sdk import WebClient
from slack_sdk.errors import SlackApiError
from config import config

class SlackWrapper:
    def __init__(self):
        self.client = WebClient(token=config.SLACK_BOT_TOKEN)

    def post_alert(self, text: str):
        try:
            self.client.chat_postMessage(
                channel=config.SLACK_CHANNEL, 
                text=text,
                unfurl_links=False
            )
            print("✅ Slack alert sent!")
        except SlackApiError as e:
            print(f"❌ Slack error: {e.response['error']}")</code></pre>
                    </div>

                    <!-- facade.py -->
                    <div class="mb-10">
                        <div class="code-header px-6 py-3 rounded-t-3xl flex items-center justify-between text-xs font-medium">
                            <span>facade.py (the orchestration layer)</span>
                        </div>
                        <pre class="bg-zinc-950 text-emerald-300 p-8 rounded-b-3xl overflow-auto"><code>from wrappers.openai_wrapper import OpenAIWrapper
from wrappers.stripe_wrapper import StripeWrapper
from wrappers.slack_wrapper import SlackWrapper
from domain import IssueAnalysis, CustomerStatus

class SupportFacade:
    def __init__(self):
        self.openai = OpenAIWrapper()
        self.stripe = StripeWrapper()
        self.slack = SlackWrapper()

    def process_support_ticket(self, email: str, issue: str):
        # Step 1: Analyze the issue with AI
        analysis: IssueAnalysis = self.openai.analyze_issue(issue)
        
        # Step 2: Look up customer in Stripe
        status: CustomerStatus = self.stripe.get_customer_status(email)
        
        # Step 3: Determine priority (premium users get escalated)
        priority = "HIGH" if status.is_premium else analysis.priority.upper()
        
        # Step 4: Build alert message
        alert = f"""🚨 *New Support Ticket*

📧 *Email:* {email}
📝 *Summary:* {analysis.summary}
🏷️ *Category:* {analysis.category}
⚡ *Priority:* {priority}
💎 *Premium User:* {"Yes" if status.is_premium else "No"}
📊 *Subscription:* {status.subscription_status or "N/A"}

*Original Issue:* {issue[:200]}..."""

        # Step 5: Send to Slack
        self.slack.post_alert(alert)
        
        return {
            "analysis": analysis,
            "customer_status": status,
            "priority": priority,
            "alert_sent": True
        }</code></pre>
                    </div>

                    <!-- main.py -->
                    <div>
                        <div class="code-header px-6 py-3 rounded-t-3xl flex items-center justify-between text-xs font-medium">
                            <span>main.py (CLI entry point)</span>
                        </div>
                        <pre class="bg-zinc-950 text-emerald-300 p-8 rounded-b-3xl overflow-auto"><code>import typer
from facade import SupportFacade

app = typer.Typer(help="Support Ticket Router - AI-powered support triage")

@app.command()
def process(email: str, issue: str):
    """
    Process a support ticket: analyze with AI, check customer status, alert team.
    
    Example: python main.py --email "user@example.com" --issue "My payment failed"
    """
    facade = SupportFacade()
    result = facade.process_support_ticket(email=email, issue=issue)
    
    print(f"\n✅ Ticket processed!")
    print(f"   Category: {result['analysis'].category}")
    print(f"   Priority: {result['priority']}")
    print(f"   Premium: {result['customer_status'].is_premium}")

if __name__ == "__main__":
    app()</code></pre>
                    </div>
                </div>
            </div>
        </div>

        <!-- RUN IT -->
        <div class="mb-20 bg-gradient-to-br from-blue-50 to-indigo-50 border border-blue-100 rounded-3xl p-10">
            <h2 class="text-3xl font-semibold mb-6">Run It</h2>
            <pre class="bg-white shadow-inner border border-blue-100 text-zinc-800 p-8 rounded-3xl overflow-auto"><code class="text-sm"># 1. Set up environment
cp .env.example .env
# Edit .env with your real API keys

# 2. Run the tool
python main.py --email "test@example.com" --issue "My payment keeps failing!"

# 3. Test different scenarios
python main.py --email "premium@company.com" --issue "URGENT: System down, losing revenue!"
python main.py --email "new@user.com" --issue "How do I reset my password?"</code></pre>
        </div>

        <!-- EXTENSIONS TABLE -->
        <div class="mb-20">
            <h2 class="text-3xl font-semibold mb-6">Extensions to Level Up (Levels 4-6)</h2>
            <div class="bg-white rounded-3xl shadow-sm border border-zinc-100 overflow-hidden">
                <table class="w-full">
                    <thead class="bg-zinc-100">
                        <tr>
                            <th class="px-8 py-5 text-left font-medium text-zinc-500">Extension</th>
                            <th class="px-8 py-5 text-left font-medium text-zinc-500">What You Learn</th>
                            <th class="px-8 py-5 text-left font-medium text-zinc-500">Red Teaming Connection</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-zinc-100 text-sm">
                        <tr>
                            <td class="px-8 py-6 font-medium">Add retries with tenacity</td>
                            <td class="px-8 py-6 text-zinc-600">Error resilience</td>
                            <td class="px-8 py-6 text-zinc-600">Red team tools must survive API failures</td>
                        </tr>
                        <tr>
                            <td class="px-8 py-6 font-medium">Add circuit breaker</td>
                            <td class="px-8 py-6 text-zinc-600">Prevent cascade failures</td>
                            <td class="px-8 py-6 text-zinc-600">Protect against malicious API abuse</td>
                        </tr>
                        <tr>
                            <td class="px-8 py-6 font-medium">Make async with asyncio</td>
                            <td class="px-8 py-6 text-zinc-600">Concurrent API calls</td>
                            <td class="px-8 py-6 text-zinc-600">Faster multi-target attacks</td>
                        </tr>
                        <tr>
                            <td class="px-8 py-6 font-medium">Add Gmail wrapper</td>
                            <td class="px-8 py-6 text-zinc-600">4-wrapper chain</td>
                            <td class="px-8 py-6 text-zinc-600">Email exfiltration testing</td>
                        </tr>
                        <tr>
                            <td class="px-8 py-6 font-medium">Add Notion wrapper</td>
                            <td class="px-8 py-6 text-zinc-600">5-wrapper chain</td>
                            <td class="px-8 py-6 text-zinc-600">Data persistence in attacks</td>
                        </tr>
                        <tr>
                            <td class="px-8 py-6 font-medium">AI agent router</td>
                            <td class="px-8 py-6 text-zinc-600">Dynamic wrapper selection</td>
                            <td class="px-8 py-6 text-zinc-600">LLM decides which APIs to call</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>

        <!-- CONNECTION TO AI RED TEAMING -->
        <div class="mb-20 bg-zinc-900 text-white rounded-3xl p-12">
            <h2 class="text-3xl font-semibold mb-8 text-white">Connection to AI Red Teaming</h2>
            <div class="max-w-2xl text-zinc-300 leading-relaxed text-lg">
                This exact pattern powers red team tools:
                <div class="mt-8 bg-zinc-800 p-8 rounded-3xl font-mono text-sm leading-relaxed">
                    Garak finds vulnerability<br>
                     ↓<br>
                    OpenAI analyzes exploit path<br>
                     ↓<br>
                    Slack alerts security team<br>
                     ↓<br>
                    Notion documents findings<br>
                     ↓<br>
                    Jira creates ticket
                </div>
            </div>
            <div class="mt-10 text-amber-400 text-sm font-medium flex items-center gap-x-3">
                <i class="fa-solid fa-shield-halved"></i>
                <span>Security testing this composition is AI red teaming</span>
            </div>
            <ul class="mt-6 space-y-4 text-zinc-400">
                <li class="flex gap-x-3">• Can prompt injection trick the AI into calling Stripe → Gmail (data exfil)?</li>
                <li class="flex gap-x-3">• Can the agent be convinced to skip the Slack alert (cover tracks)?</li>
                <li class="flex gap-x-3">• What happens if the OpenAI wrapper returns malformed JSON?</li>
            </ul>
        </div>

        <!-- CHECKLIST -->
        <div class="mb-12">
            <h2 class="text-3xl font-semibold mb-8">Your Checklist</h2>
            <div class="grid grid-cols-1 gap-4 text-lg">
                <div class="flex items-center gap-x-4 bg-white p-6 rounded-3xl border border-zinc-100">
                    <input type="checkbox" class="w-6 h-6 accent-blue-600" checked> 
                    <span>Project structure created</span>
                </div>
                <div class="flex items-center gap-x-4 bg-white p-6 rounded-3xl border border-zinc-100">
                    <input type="checkbox" class="w-6 h-6 accent-blue-600"> 
                    <span>All 5 files implemented</span>
                </div>
                <div class="flex items-center gap-x-4 bg-white p-6 rounded-3xl border border-zinc-100">
                    <input type="checkbox" class="w-6 h-6 accent-blue-600"> 
                    <span>.env configured with test keys</span>
                </div>
                <div class="flex items-center gap-x-4 bg-white p-6 rounded-3xl border border-zinc-100">
                    <input type="checkbox" class="w-6 h-6 accent-blue-600"> 
                    <span>python main.py runs successfully</span>
                </div>
                <div class="flex items-center gap-x-4 bg-white p-6 rounded-3xl border border-zinc-100">
                    <input type="checkbox" class="w-6 h-6 accent-blue-600"> 
                    <span>Tested with 3+ different issue types</span>
                </div>
                <div class="flex items-center gap-x-4 bg-white p-6 rounded-3xl border border-zinc-100">
                    <input type="checkbox" class="w-6 h-6 accent-blue-600"> 
                    <span>Observed Slack alerts received</span>
                </div>
                <div class="flex items-center gap-x-4 bg-white p-6 rounded-3xl border border-zinc-100">
                    <input type="checkbox" class="w-6 h-6 accent-blue-600"> 
                    <span>Read and understood the facade pattern</span>
                </div>
                <div class="flex items-center gap-x-4 bg-white p-6 rounded-3xl border border-zinc-100">
                    <input type="checkbox" class="w-6 h-6 accent-blue-600"> 
                    <span>Ready to add Level 4 (retries, circuit breakers)</span>
                </div>
            </div>
        </div>

        <!-- FINAL CALL TO ACTION -->
        <div class="text-center py-12 border-t border-zinc-200">
            <p class="text-2xl font-semibold text-zinc-800">Build this today — it's your foundation for everything that follows.</p>
            <p class="mt-4 text-zinc-500">Master this pattern and you’re building the same systems you’ll be paid to attack and defend.</p>
        </div>

    </div>

    <script>
        // Tailwind script init
        function initTailwind() {
            // Already using CDN classes - no extra needed
        }
        window.onload = initTailwind;
    </script>
</body>
</html>
