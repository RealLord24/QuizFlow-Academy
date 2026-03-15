export function App() {
  const stats = [
    { label: "MCQs completed", value: "45K+" },
    { label: "Practice exams", value: "1,200" },
    { label: "Course summaries", value: "680" },
    { label: "Daily active learners", value: "32K" },
  ];

  const steps = [
    {
      step: "Step 1",
      title: "Pick a subject",
      description: "Choose a course and focus topic to build a personalized practice path.",
    },
    {
      step: "Step 2",
      title: "Practice with MCQs",
      description: "Solve targeted MCQs with instant feedback, hints, and explanations.",
    },
    {
      step: "Step 3",
      title: "Take a mock exam",
      description: "Simulate real exam conditions, track your score, and review mistakes.",
    },
    {
      step: "Step 4",
      title: "Revise with summaries",
      description: "Use concise course notes and cheat sheets to reinforce learning.",
    },
  ];

  const practiceModes = [

    {
      title: "MCQ drills",
      description: "Targeted question sets with instant feedback and hints.",
      items: ["Adaptive difficulty", "Topic filters", "Explain answers"],
    },
    {
      title: "Timed practice exams",
      description: "Full-length exams with timer, scoring, and review reports.",
      items: ["Section timer", "Score analytics", "Weakness tracker"],
    },
    {
      title: "Course summaries",
      description: "Concise lesson notes, cheat sheets, and formula banks.",
      items: ["Key concepts", "Quick refresh", "Downloadable PDFs"],
    },
  ];

  const features = [
    {
      title: "Personalized study plans",
      description: "Auto-generated schedules based on your goals and availability.",
    },
    {
      title: "Question vault",
      description: "Thousands of MCQs tagged by subject, year, and difficulty.",
    },
    {
      title: "Exam simulations",
      description: "Mirror real exam conditions and track readiness scores.",
    },
    {
      title: "Summary library",
      description: "Curated notes with step-by-step solutions and flashcards.",
    },
  ];

  const subjects = [
    {
      label: "Mathematics",
      topics: ["Algebra", "Calculus", "Statistics"],
    },
    {
      label: "Science",
      topics: ["Biology", "Physics", "Chemistry"],
    },
    {
      label: "Languages",
      topics: ["Grammar", "Vocabulary", "Comprehension"],
    },
  ];

  const testimonials = [
    {
      quote: "The MCQ drills helped me improve my score by 22% in two weeks.",
      name: "Tania Patel",
      role: "Entrance Exam Candidate",
    },
    {
      quote: "Practice exams feel exactly like the real test. I finally feel ready.",
      name: "Marcus Lee",
      role: "Senior High Student",
    },
    {
      quote: "Course summaries are my go-to before every quiz. So easy to review.",
      name: "Alina Santos",
      role: "First-year Student",
    },
  ];

  return (
    <div className="min-h-screen bg-slate-950 text-white">
      <header className="border-b border-white/10 bg-slate-950/80 backdrop-blur">
        <div className="mx-auto flex w-full max-w-6xl items-center justify-between px-6 py-5">
          <div className="flex items-center gap-3">
            <div className="flex h-11 w-11 items-center justify-center rounded-2xl bg-gradient-to-br from-indigo-400 via-sky-400 to-emerald-400 text-slate-900">
              <svg viewBox="0 0 24 24" className="h-6 w-6" fill="currentColor">
                <path d="M5 3a2 2 0 0 0-2 2v13a1 1 0 0 0 1.45.9L9 16.5l4.55 2.4A1 1 0 0 0 15 18V5a2 2 0 0 0-2-2H5Zm11 4h3v12a2 2 0 0 1-2 2H8.5a.5.5 0 0 1-.5-.5v-1.1l4-2.1L16 19V7Z" />
              </svg>
            </div>
            <div>
              <p className="text-sm font-semibold uppercase tracking-[0.2em] text-sky-300">Student Practice Hub</p>
              <p className="text-lg font-semibold">QuizFlow Academy</p>
            </div>
          </div>
          <nav className="hidden items-center gap-6 text-sm text-slate-200 md:flex">
            <a className="transition hover:text-sky-200" href="#practice">
              Practice modes
            </a>
            <a className="transition hover:text-sky-200" href="#features">
              Features
            </a>
            <a className="transition hover:text-sky-200" href="#subjects">
              Subjects
            </a>
            <a className="transition hover:text-sky-200" href="#results">
              Results
            </a>
          </nav>
          <button className="rounded-full bg-white px-5 py-2 text-sm font-semibold text-slate-900 transition hover:bg-sky-100">
            Start practicing
          </button>
        </div>
      </header>

      <main>
        <section className="relative overflow-hidden">
          <div className="absolute inset-0 bg-[radial-gradient(circle_at_top,_rgba(56,189,248,0.25),_transparent_55%)]" />
          <div className="relative mx-auto flex w-full max-w-6xl flex-col gap-12 px-6 pb-20 pt-16 lg:flex-row lg:items-center">
            <div className="flex-1 space-y-6">
              <p className="inline-flex items-center gap-2 rounded-full border border-sky-400/30 bg-sky-400/10 px-4 py-1 text-xs font-semibold uppercase tracking-[0.2em] text-sky-200">
                MCQs, mock exams, and summaries in one place
              </p>
              <h1 className="text-4xl font-semibold leading-tight sm:text-5xl">
                Practice smarter with MCQs, simulated exams, and quick course summaries.
              </h1>
              <p className="text-lg text-slate-300">
                QuizFlow Academy helps students master topics faster with targeted drills, full-length mock exams, and
                bite-sized study notes tailored for revision.
              </p>
              <div className="flex flex-wrap gap-4">
                <button className="rounded-full bg-sky-400 px-6 py-3 text-sm font-semibold text-slate-900 transition hover:bg-sky-300">
                  Browse MCQs
                </button>
                <button className="rounded-full border border-white/20 px-6 py-3 text-sm font-semibold text-white transition hover:border-sky-200 hover:text-sky-200">
                  Take a practice exam
                </button>
              </div>
              <div className="grid gap-6 sm:grid-cols-2">
                {stats.map((stat) => (
                  <div key={stat.label} className="rounded-2xl border border-white/10 bg-white/5 p-4">
                    <p className="text-2xl font-semibold text-white">{stat.value}</p>
                    <p className="text-sm text-slate-300">{stat.label}</p>
                  </div>
                ))}
              </div>
            </div>
            <div className="flex-1">
              <div className="rounded-3xl border border-white/10 bg-gradient-to-br from-white/10 via-white/5 to-transparent p-6 shadow-2xl">
                <div className="space-y-6">
                  <div className="flex items-center justify-between">
                    <div>
                      <p className="text-sm text-slate-300">Today’s practice</p>
                      <p className="text-xl font-semibold">Mathematics MCQ Drill</p>
                    </div>
                    <span className="rounded-full bg-emerald-400/20 px-3 py-1 text-xs font-semibold text-emerald-200">
                      15 questions
                    </span>
                  </div>
                  <div className="space-y-4">
                    {[
                      "Linear equations",
                      "Probability basics",
                      "Functions & graphs",
                    ].map((item, index) => (
                      <div
                        key={item}
                        className="flex items-center justify-between rounded-2xl border border-white/10 bg-slate-950/40 px-4 py-3"
                      >
                        <div className="flex items-center gap-3">
                          <span className="flex h-9 w-9 items-center justify-center rounded-xl bg-sky-400/20 text-sm font-semibold text-sky-200">
                            {index + 1}
                          </span>
                          <p className="text-sm text-slate-200">{item}</p>
                        </div>
                        <span className="text-xs text-slate-400">8 min</span>
                      </div>
                    ))}
                  </div>
                  <div className="rounded-2xl border border-sky-400/30 bg-sky-400/10 p-4">
                    <p className="text-sm font-semibold text-sky-200">Recommended next exam</p>
                    <p className="text-xs text-sky-100/80">
                      Full-length mock: 90 minutes • 75 questions • Score analysis included.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>

        <section className="mx-auto w-full max-w-6xl px-6 py-16">
          <div className="grid gap-10 lg:grid-cols-[0.9fr_1.1fr] lg:items-center">
            <div className="space-y-4">
              <p className="text-sm font-semibold uppercase tracking-[0.2em] text-sky-300">How it works</p>
              <h2 className="text-3xl font-semibold">Create your study flow in four guided steps.</h2>
              <p className="text-slate-300">
                We will build this together. Start by choosing a subject, then move to MCQs, practice exams, and
                summaries for quick revision.
              </p>
              <button className="rounded-full border border-white/20 px-5 py-2 text-sm font-semibold text-white transition hover:border-sky-200 hover:text-sky-200">
                See sample study plan
              </button>
            </div>
            <div className="grid gap-4 sm:grid-cols-2">
              {steps.map((step) => (
                <div key={step.step} className="rounded-3xl border border-white/10 bg-white/5 p-6">
                  <p className="text-xs font-semibold uppercase tracking-[0.2em] text-sky-200">{step.step}</p>
                  <h3 className="mt-3 text-lg font-semibold">{step.title}</h3>
                  <p className="mt-2 text-sm text-slate-300">{step.description}</p>
                </div>
              ))}
            </div>
          </div>
        </section>

        <section id="practice" className="mx-auto w-full max-w-6xl px-6 py-16">
          <div className="flex flex-col gap-6 lg:flex-row lg:items-end lg:justify-between">
            <div className="space-y-3">
              <p className="text-sm font-semibold uppercase tracking-[0.2em] text-sky-300">Practice modes</p>
              <h2 className="text-3xl font-semibold">Choose how you want to practice today.</h2>
              <p className="max-w-2xl text-slate-300">
                Mix MCQ drills, timed exams, and quick summaries to stay consistent and exam-ready.
              </p>
            </div>
            <button className="rounded-full border border-white/20 px-5 py-2 text-sm font-semibold text-white transition hover:border-sky-200 hover:text-sky-200">
              Build a custom plan
            </button>
          </div>
          <div className="mt-10 grid gap-6 lg:grid-cols-3">
            {practiceModes.map((mode) => (
              <div key={mode.title} className="rounded-3xl border border-white/10 bg-white/5 p-6">
                <h3 className="text-xl font-semibold">{mode.title}</h3>
                <p className="mt-3 text-sm text-slate-300">{mode.description}</p>
                <div className="mt-6 space-y-3">
                  {mode.items.map((item) => (
                    <div key={item} className="flex items-center gap-3 text-sm text-slate-200">
                      <span className="h-2 w-2 rounded-full bg-sky-400" />
                      {item}
                    </div>
                  ))}
                </div>
              </div>
            ))}
          </div>
        </section>

        <section className="bg-slate-900/60">
          <div className="mx-auto w-full max-w-6xl px-6 py-16">
            <div className="grid gap-10 lg:grid-cols-[1.05fr_0.95fr] lg:items-center">
              <div className="rounded-3xl border border-white/10 bg-white/5 p-8">
                <p className="text-sm font-semibold uppercase tracking-[0.2em] text-sky-300">Step 1</p>
                <h2 className="mt-3 text-3xl font-semibold">Select a course and focus topic.</h2>
                <p className="mt-4 text-slate-300">
                  Choose from math, science, languages, or any course your instructor assigns. Pick a topic to start the
                  MCQ journey.
                </p>
                <div className="mt-6 flex flex-wrap gap-3">
                  {["Mathematics", "Physics", "Biology", "English"].map((topic) => (
                    <span
                      key={topic}
                      className="rounded-full border border-white/10 bg-slate-950/40 px-4 py-2 text-xs text-slate-200"
                    >
                      {topic}
                    </span>
                  ))}
                </div>
              </div>
              <div className="space-y-6">
                <div className="rounded-3xl border border-emerald-400/30 bg-emerald-400/10 p-6">
                  <p className="text-sm font-semibold uppercase tracking-[0.2em] text-emerald-200">Step 2</p>
                  <h3 className="mt-3 text-2xl font-semibold">Practice MCQs with instant feedback.</h3>
                  <p className="mt-3 text-sm text-emerald-100/80">
                    Answer questions, review explanations, and track accuracy as you go.
                  </p>
                </div>
                <div className="rounded-3xl border border-sky-400/30 bg-sky-400/10 p-6">
                  <p className="text-sm font-semibold uppercase tracking-[0.2em] text-sky-200">Step 3</p>
                  <h3 className="mt-3 text-2xl font-semibold">Take a timed practice exam.</h3>
                  <p className="mt-3 text-sm text-sky-100/80">
                    Build stamina with full-length exams that mirror the real test format.
                  </p>
                </div>
                <div className="rounded-3xl border border-purple-400/30 bg-purple-400/10 p-6">
                  <p className="text-sm font-semibold uppercase tracking-[0.2em] text-purple-200">Step 4</p>
                  <h3 className="mt-3 text-2xl font-semibold">Review with quick summaries.</h3>
                  <p className="mt-3 text-sm text-purple-100/80">
                    Lock in knowledge with course notes, formula sheets, and mini flashcards.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </section>

        <section id="features" className="bg-slate-900/60">
          <div className="mx-auto w-full max-w-6xl px-6 py-16">
            <div className="grid gap-10 lg:grid-cols-[1.1fr_0.9fr]">
              <div className="space-y-4">
                <p className="text-sm font-semibold uppercase tracking-[0.2em] text-sky-300">Learning tools</p>
                <h2 className="text-3xl font-semibold">Stay on track with detailed performance insights.</h2>
                <p className="text-slate-300">
                  Track accuracy, speed, and revision frequency with reports designed to highlight your next best move.
                </p>
                <div className="mt-8 grid gap-5">
                  {features.map((feature) => (
                    <div key={feature.title} className="rounded-2xl border border-white/10 bg-white/5 p-5">
                      <h3 className="text-lg font-semibold">{feature.title}</h3>
                      <p className="mt-2 text-sm text-slate-300">{feature.description}</p>
                    </div>
                  ))}
                </div>
              </div>
              <div className="rounded-3xl border border-white/10 bg-gradient-to-br from-sky-400/20 via-white/5 to-transparent p-8">
                <div className="space-y-6">
                  <div className="flex items-center justify-between">
                    <div>
                      <p className="text-sm text-slate-300">Exam readiness</p>
                      <p className="text-xl font-semibold">Weekly snapshot</p>
                    </div>
                    <span className="text-xs text-sky-200">Updated 2h ago</span>
                  </div>
                  <div className="space-y-4">
                    {[
                      { label: "Accuracy", value: "82%", width: "82%" },
                      { label: "Questions attempted", value: "460", width: "70%" },
                      { label: "Time per question", value: "52s", width: "64%" },
                      { label: "Summary reviews", value: "18", width: "58%" },
                    ].map((item) => (
                      <div key={item.label}>
                        <div className="flex items-center justify-between text-sm">
                          <span className="text-slate-200">{item.label}</span>
                          <span className="text-sky-200">{item.value}</span>
                        </div>
                        <div className="mt-2 h-2 w-full rounded-full bg-white/10">
                          <div className="h-2 rounded-full bg-sky-400" style={{ width: item.width }} />
                        </div>
                      </div>
                    ))}
                  </div>
                  <div className="rounded-2xl border border-white/10 bg-slate-950/40 p-4 text-sm text-slate-300">
                    <p className="font-semibold text-white">Coach tip</p>
                    <p className="mt-1">
                      Review the Algebra summary before the next timed exam to boost speed.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>

        <section id="subjects" className="mx-auto w-full max-w-6xl px-6 py-16">
          <div className="grid gap-10 lg:grid-cols-[0.95fr_1.05fr]">
            <div className="rounded-3xl border border-white/10 bg-white/5 p-8">
              <h2 className="text-3xl font-semibold">Subjects organized for faster revision.</h2>
              <p className="mt-3 text-slate-300">
                Jump into targeted question sets and summary guides based on the syllabus you are studying.
              </p>
              <div className="mt-8 space-y-4">
                {subjects.map((subject) => (
                  <div key={subject.label} className="rounded-2xl border border-white/10 bg-slate-950/40 p-4">
                    <p className="text-sm font-semibold text-white">{subject.label}</p>
                    <div className="mt-3 flex flex-wrap gap-2">
                      {subject.topics.map((topic) => (
                        <span
                          key={topic}
                          className="rounded-full border border-sky-400/40 bg-sky-400/10 px-3 py-1 text-xs text-sky-200"
                        >
                          {topic}
                        </span>
                      ))}
                    </div>
                  </div>
                ))}
              </div>
            </div>
            <div className="space-y-6">
              <div className="rounded-3xl border border-white/10 bg-gradient-to-br from-emerald-400/15 via-white/10 to-transparent p-6">
                <h3 className="text-xl font-semibold">Sample MCQ</h3>
                <p className="mt-2 text-sm text-slate-300">
                  Which formula represents the area of a circle?
                </p>
                <div className="mt-6 grid gap-3 text-sm text-slate-200">
                  {[
                    "A = 2πr",
                    "A = πr²",
                    "A = πd",
                    "A = r²",
                  ].map((option) => (
                    <div key={option} className="flex items-center gap-3 rounded-2xl border border-white/10 bg-slate-950/40 px-4 py-3">
                      <span className="h-2 w-2 rounded-full bg-emerald-400" />
                      {option}
                    </div>
                  ))}
                </div>
                <button className="mt-6 text-sm font-semibold text-emerald-200">Reveal answer →</button>
              </div>
              <div className="rounded-3xl border border-white/10 bg-white/5 p-6">
                <h3 className="text-xl font-semibold">Upcoming practice exams</h3>
                <div className="mt-4 space-y-3 text-sm text-slate-200">
                  {[
                    "STEM Mock Exam • Friday 6 PM",
                    "Language Skills Quiz • Saturday 10 AM",
                    "Statistics Challenge • Sunday 4 PM",
                  ].map((exam) => (
                    <div key={exam} className="flex items-center gap-2">
                      <span className="h-2 w-2 rounded-full bg-sky-400" />
                      {exam}
                    </div>
                  ))}
                </div>
              </div>
            </div>
          </div>
        </section>

        <section id="results" className="bg-slate-900/60">
          <div className="mx-auto w-full max-w-6xl px-6 py-16">
            <div className="flex flex-col gap-6 lg:flex-row lg:items-end lg:justify-between">
              <div className="space-y-3">
                <p className="text-sm font-semibold uppercase tracking-[0.2em] text-sky-300">Student results</p>
                <h2 className="text-3xl font-semibold">Proof that practice makes progress.</h2>
                <p className="max-w-2xl text-slate-300">
                  Learners improve accuracy, confidence, and exam scores by practicing consistently with QuizFlow.
                </p>
              </div>
              <button className="rounded-full border border-white/20 px-5 py-2 text-sm font-semibold text-white transition hover:border-sky-200 hover:text-sky-200">
                View success stories
              </button>
            </div>
            <div className="mt-10 grid gap-6 md:grid-cols-3">
              {testimonials.map((testimonial) => (
                <div key={testimonial.name} className="rounded-3xl border border-white/10 bg-white/5 p-6">
                  <p className="text-sm text-slate-200">“{testimonial.quote}”</p>
                  <p className="mt-4 text-xs font-semibold text-sky-200">{testimonial.name}</p>
                  <p className="text-xs text-slate-400">{testimonial.role}</p>
                </div>
              ))}
            </div>
          </div>
        </section>

        <section className="mx-auto w-full max-w-6xl px-6 py-16">
          <div className="rounded-3xl border border-sky-400/30 bg-gradient-to-br from-sky-400/20 via-white/5 to-transparent p-10">
            <div className="grid gap-8 lg:grid-cols-[1.1fr_0.9fr] lg:items-center">
              <div>
                <p className="text-sm font-semibold uppercase tracking-[0.2em] text-sky-200">Ready to practice</p>
                <h2 className="mt-3 text-3xl font-semibold">Start your next MCQ session today.</h2>
                <p className="mt-3 text-slate-200">
                  Build a personalized study streak with daily quizzes, weekly exams, and quick summary refreshers.
                </p>
              </div>
              <div className="flex flex-col gap-3 sm:flex-row">
                <button className="rounded-full bg-sky-400 px-6 py-3 text-sm font-semibold text-slate-900 transition hover:bg-sky-300">
                  Start free practice
                </button>
                <button className="rounded-full border border-white/20 px-6 py-3 text-sm font-semibold text-white transition hover:border-sky-200 hover:text-sky-200">
                  Download the app
                </button>
              </div>
            </div>
          </div>
        </section>
      </main>

      <footer className="border-t border-white/10 bg-slate-950">
        <div className="mx-auto flex w-full max-w-6xl flex-col gap-6 px-6 py-10 sm:flex-row sm:items-center sm:justify-between">
          <div>
            <p className="text-sm font-semibold">QuizFlow Academy</p>
            <p className="text-xs text-slate-400">Helping students practice MCQs, mock exams, and summaries daily.</p>
          </div>
          <div className="flex flex-wrap gap-4 text-xs text-slate-400">
            <span>Support</span>
            <span>Privacy</span>
            <span>Terms</span>
            <span>Contact</span>
          </div>
        </div>
      </footer>
    </div>
  );
}
